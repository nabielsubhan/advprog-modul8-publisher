## Nama   : Muhammad Nabiel Subhan
## NPM    : 2206081553
## Kelas  : AdPro B

### How many data your publisher program will send to the message broker in one run?
Dari kode program yang ada, publisher akan mengirimkan 5 data ke message broker karena terdapat 5 kali pemanggilan method `publish_event` pada instance dari `CrosstownBus`.

### The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean? 
Publisher dan Subscriber menggunakan URL yang sama menandakan bahwa keduanya memiliki koneksi ke AMQP broker yang sama. Perbedaannya adalah Publisher akan mem-*publish* data ke AMQP broker, sedangkan Subscriber akan me-*listen* data dari AMQP broker.

### Running RabbitMQ as message broker
<p align="center">
  <img src="images\rabbitmq-running.png" />
</p>