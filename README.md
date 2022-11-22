# SAKITA Cinema Booking App-MVP

In this app user will be able to search, filter and view details of movies.

## Functionalities

- Movies can be observed in a list.
- Movies have three categories (popular, top rated, upcoming).
- Clicking on an item opens detail screen for that item.
- The app has 2 modes(online and offline). In Online mode items are obtained from API, presented in an endlessList and saved in a database. In Offline mode items are obtained from a database.
- Movies can be filtered by name, rating and release date in offline mode.

## Architecture, Structure and Patterns

The app is based in MVP(Model View Presenter) with three layers:
- Data
- Presenter
- View

App implements Dependency injection and Reactive programming (Observable-Observer Pattern).

## Details, Tools and Practices.

- Advance Graddle system. Using separated files for projects settings and dependencies.
- Using styles for repeated UI components.
- Packaging app by layer, and every layer by feature.
- App implements single responsibility principle that means every component of code (class, function, variable) is used for one and only one task or purpose.
- App implements clean code principle that means programmer should keep classes as simpler as possible in order to be testable, code should implement single responsibility principle explained above, classes should have as few as possible dependencies, and programmer should follow universal coding styles in order to make code maintainable. 

## Libraries
- Networking (Fast Android Networking).
- Fonts (Caligraphy).
- Image Loading and Cache (Glide).
- Parsing data (Gson).
- DataBase (greenDao).
- DebugDatabase (DebugDatabase).
- Alerts (SweetAlertLibrary).
- Dependency Injection (Dagger2).
- Reactive (RxJava 2).
- View Injection(ButterKnife).
- Logger(Timber).

## Project Structure.



    

 
  

    
   
    








