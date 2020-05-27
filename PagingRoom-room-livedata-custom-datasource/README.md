# Room Paging Library: `LiveData` and custom `ItemKeyedDataSource`

[![Build Status](https://travis-ci.org/jshvarts/PagingRoom.svg?branch=room-livedata-custom-datasource)](https://travis-ci.org/jshvarts/PagingRoom) [![Android Weekly](https://img.shields.io/badge/Android%20Weekly-%23329-2CA3E6.svg?style=flat)](http://androidweekly.net/issues/issue-329)

Companion article: [Exploring Paging Library from Jetpack](https://proandroiddev.com/exploring-paging-library-from-jetpack-c661c7399662)

Demonstrates using [Paging Library](https://developer.android.com/topic/libraries/architecture/paging/) with paging using `LiveData` and custom `ItemKeyedDataSource`. 

## Other Branches
1) [master](https://github.com/jshvarts/PagingRoom) -- common setup with no paging used
2) [room-livedata](https://github.com/jshvarts/PagingRoom/tree/room-livedata) -- paging using `LiveData` and default `DataSource` 
3) [room-rxjava](https://github.com/jshvarts/PagingRoom/tree/room-rxjava) -- paging using `RxJava` and default `DataSource` 
4) [room-livedata-custom-datasource](https://github.com/jshvarts/PagingRoom/tree/room-livedata-custom-datasource) -- **(this branch)** paging using `LiveData` and custom `ItemKeyedDataSource`

## Libraries
* [Paging Library](https://developer.android.com/topic/libraries/architecture/paging/)
* [Room Persistence Library](https://developer.android.com/topic/libraries/architecture/room)
* [Navigation Architecture Component](https://developer.android.com/topic/libraries/architecture/navigation/)
* [Lifecycle Architecture Component](https://developer.android.com/topic/libraries/architecture/lifecycle)
* [Dagger Android 2.17](https://google.github.io/dagger/android.html)
* [RxJava](https://github.com/ReactiveX/RxJava)

## App Design
The app follows **Clean Architecture** Principles to make it cleaner, more readable and maintainable.
* Separate layers: Data, Domain, Presentation and UI
* MVVM architecture for clean separation between UI and Presentation and below
* Repository pattern
* Mapping model between data and domain (`NoteEntity` and `Note`)   

## License

    Copyright 2018 James Shvarts

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
