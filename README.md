# MyMovies
A Flutter app showcasing a list of popular movies from MovieDB. 

I have covered the following importamt topics in this app:

- Repository and BLoC pattern

- Separating UI and business logic

- Dependency Injection

- Unit and Integration testing

## Run Project

1.Adding inject.dart

Create a folder and name itinjection (you can name anything)inside MyMovies the directory. Open your terminal and navigate to the folder you just created and run the below command:
```
git submodule add https://github.com/google/inject.dart
```

2.run command

inside MyMovies the directory open your terminal and run the below command:
```
flutter packages pub run build_runner build --delete-conflicting-outputs
```

## Cleanup

After successful code generation. You might see many generated files added to your project.
Don’t panic! This is normal. You can delete all the *.inject.dart and *.summary files except bloc_injector.inject.dart
To make this task automated use this script:

https://github.com/RezaEsafandiary/remove_DI_file_from_flutter


## Contact me:
reza.esfandiary.dev@gmail.com 

LinkedIn profile: 
https://www.linkedin.com/in/reza-esfandiary/
