## Test For DevCode 

Ubah file docker-compose.yml sesuikan nama image dg nama image kamu

Jalankan aplikasi kamu beserta mysqlnya

``` docker-compose up -d ```

Jalankan pengujian aplikasimu dengan

``` docker run --net devcode -e API_URL=http://app:3030 --link app monsterup/devcode-unit-test-1 ```
