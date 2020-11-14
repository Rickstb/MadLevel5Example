# MadLevel5Example vragen level 5

#1 What are the parts that Android Architecture Components consist of?

All the Android Architecture Components are as follows:

Data Binding: It helps in declaratively binding UI elements to in our layout to data sources of our app.
Lifecycles: It manages activity and fragment lifecycles of our app, survives configuration changes, avoids memory leaks and easily loads data into our UI.
LiveData: It notifies views of any database changes. Use LiveData to build data objects that notify views when the underlying database changes.
Navigation: It handles everything needed for in-app navigation in Android application.
Paging: It helps in gradually loading information on demand from our data source.
Room: It is a SQLite object mapping library. Use it to Avoid boilerplate code and easily convert SQLite table data to Java objects. Room provides compile time checks of SQLite statements and can return RxJava, Flowable and LiveData observables.
ViewModel: It manages UI-related data in a lifecycle-conscious way. It stores UI-related data that isn't destroyed on app rotations.
WorkManager: It manages every background jobs in Android with the circumstances we choose.

#2Which design principle is followed by the Android Architecture Components?
Android architecture components are a collection of libraries that help you design robust, testable, and maintainable apps. Start with classes for managing your UI component lifecycle and handling data persistence.

#3 What is the purpose of LiveData?
It notifies views of any database changes. Use LiveData to build data objects that notify views when the underlying database changes.
// LiveData is an observable data holder class. Unlike a regular observable, LiveData is lifecycle-aware, meaning it respects the lifecycle of other app components, such as activities, fragments, or services. This awareness ensures LiveData only updates app component observers that are in an active lifecycle state.

#4What is the purpose of a ViewModel?
It manages UI-related data in a lifecycle-conscious way. It stores UI-related data that isn't destroyed on app rotations.
