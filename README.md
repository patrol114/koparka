# Koparka

Wersja podstawowa
Podstawowa wersja jest dobra dla lokalnej maszyny, ponieważ jest łatwa, ale jeśli potrzebujesz uruchomić górnika na innych maszynach, spójrz na zaawansowaną wersję.

 ```sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
 ```git clone https://github.com/patrol114/koparka.git
 ```mkdir xmrig/build && cd xmrig/build
 ```cmake ..
 ```make -j$(nproc)
