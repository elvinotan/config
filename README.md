# Config
Konfigurasi ini di buat berdasarkan nama file contoh bila microservice memiliki name ```payment``` maka di sini di buat konfigurasi bernama ```payment.yml```.</br>
Apabila developer ingin membedakan nama file configurasi berdasarkan profilenya maka bisa di buat ```payment-dev.yml``` atau ```payment-prod.yml```</br>
Atau developer cukup membuat 1 file configurasi saja yaitu ```payment.yml``` dan dialamnya terdiri dari beberapa profile yang di pisahkan dengan tag ---. Dan profilenya di bedakan dgn tag ```spring.profiles```</br>
Masing masing tag indent di pisahkan oleh \n dan 2 char space

