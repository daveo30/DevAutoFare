Google-Directions-Android


The sample makes use of the Google Places API for Android in order to provide a real life example of how the library can be used.[You can check it out on the store.](https://play.google.com/store/apps/details?id=com.directions.sample)

Download
--------


Grab via Maven:
```xml
<dependency>
  <groupId>com.github.jd-alexander</groupId>
  <artifactId>library</artifactId>
  <version>1.1.0</version>
</dependency>
```
or Gradle:
```groovy
    compile 'com.github.jd-alexander:library:1.1.0'
```

Usage
-----

To calculate the route you simply instantiate a Routing object and trigger the execute function.


*You can execute the task in this manner. ( See the example for more details on the exact implementation)



``` java

        Routing routing = new Routing.Builder()
                    .travelMode(/* Travel Mode */)
                    .withListener(/* Listener that delivers routing results.*/)
                    .waypoints(/*waypoints*/)
                    .key(/*api key for quota management*/)
                    .build();
        routing.execute();
        

Contributors
------------
*   [Cyrille Berliat](https://github.com/licryle)
*   [Felipe Duarte](https://github.com/fcduarte)
*   [Kedar Sarmalkar](https://github.com/ksarmalkar)
*   [Fernando Gil](https://github.com/fgil)
*   [Furkan Tektas](https://github.com/furkantektas)
*   [João Pedro Nardari dos Santos](https://github.com/joaopedronardari)
*   [Hesham Saeed](https://github.com/HeshamSaeed)

License
--------

    Copyright 2016 Joel Dean

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.