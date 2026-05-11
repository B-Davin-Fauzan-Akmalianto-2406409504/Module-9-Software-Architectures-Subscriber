# Reflection

### a. What is AMQP?
 
AMQP merupakan singkatan dari Advanced Message Queuing Protocol, dan AMQP itu sendiri merupakan sebuah protokol (seperti HTTP) khusus untuk mengirim pesan antar aplikasi. Bedanya dengan HTTP, AMQP bersifat asynchronous sehingga tidak perlu menunggu response sebelum mengirim request kembali.

### b. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?

guest:guest@localhost:5672 merupakan URL tempat message broker dari AMQP yang kita gunakan. guest pertama merupakan username, dan guest kedua merupakan password default dari username tersebut (biasanya hanya dipakai untuk kebutuhan local). localhost:5672 menunjukkan address serta port yang digunakan.

