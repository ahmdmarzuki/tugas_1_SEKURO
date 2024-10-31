project kali ini memungkinkan kita mengontrol mouse menggunakan jari telunjuk.

menggunakan library cv2 untuk mengaktifkan kamera bawaan.
library mediapipe untuk mendeteksi tangan dan membuat landmark.
library pyautogui untuk memindahkan posisi kursor ke koordinat ujung jari telunjuk.

cara kerjanya,
mediapipe akan mengambil koordinat dari jari telunjuk, kemudian pyautogui akan memindahkan posisi kursor ke koordinat tersebut.

saya juga membuat fungsi click dimana Ketika ujung jari telunjuk dan ujung jari jempol bersentuhan, akan menjalankan fungsi tersebut.