# LatihanPersiapan5
## 1. Apa Itu MultiThreading?
Multithreading  adalah kemampuan sebuah aplikasi untuk menjalankan beberapa bagian kode secara bersamaan atau paralel. Ini dilakukan dengan menggunakan thread, yaitu unit eksekusi yang lebih ringan dibandingkan proses. Dengan multithreading, aplikasi bisa lebih responsif, meningkatkan penggunaan CPU, dan mempermudah pengembangan aplikasi yang kompleks. 

## 2. Apa Perbedaaan Antara Thread dan Runnable?

### Thread : 

Kelas Thread, komponen fundamental dalam paradigma multithreading Java, mewakili thread eksekusi. Kelas ini menyediakan metode untuk membuat dan mengendalikan thread. Ketika sebuah kelas memperluas kelas Thread, kelas tersebut pada dasarnya menjadi thread. Pekerjaan aktual yang harus dilakukan oleh thread didefinisikan dalam metode run(), yang harus ditimpa oleh kelas yang memperluas Thread.

### Runnable : 
Sebaliknya, antarmuka Runnable di Java merepresentasikan tugas yang dapat dieksekusi secara bersamaan oleh sebuah thread. Meskipun tidak mendefinisikan metode apa pun, antarmuka ini memiliki satu metode abstrak yang disebut run(). Untuk menggunakan Runnable, sebuah kelas harus mengimplementasikan antarmuka ini dan menyediakan implementasi untuk metode run().

## 3. Thread.sleep() digunakan untuk?
Thread.sleep() digunakan untuk sementara menghentikan eksekusi thread saat ini selama periode waktu yang ditentukan, dalam milidetik. Ini memungkinkan thread lain untuk menjalankan, dan setelah waktu yang ditentukan berlalu, thread yang dihentikan akan dilanjutkan. 

