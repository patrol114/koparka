# Koparka

Wersja podstawowa
Podstawowa wersja jest dobra dla lokalnej maszyny, ponieważ jest łatwa, ale jeśli potrzebujesz uruchomić górnika na innych maszynach, spójrz na zaawansowaną wersję.

1. sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
2. git clone https://github.com/patrol114/koparka.git
3. mkdir xmrig/build && cd xmrig/build
4. cmake ..
5. make -j$(nproc)
