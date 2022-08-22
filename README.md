# Simulasi_Driver_Motor_BLDC
Simulasi Driver Motor BLDC dirangkai menggunakan aplikasi Matlab/SIMULINK. Spesifikasi motor yang digunakan pada simulasi adalah motor BLDC seri BN42-43IP-03. Pada rangkaian simulasi terdapat beberapa diagram blok, yaitu Inverter, Decoder, Gate, dan Controller.
- Diagram blok Inverter berisi rangkaian enam buah MOSFET yang disusun secara pararel untuk melakukan proses pensaklaran pada tiga buah terminal fasa motor BLDC.
- Diagram blok Decoder berisi rangkaian gerbang logika yang menerima sinyal masukan dari hall sensor motor BLDC, diagram blok decoder menghasilkan sinyal keluaran sebagai nilai electromotive force (emf) tiga fasa.
- Diagram blok Gate berisi rangkaian gerbang logika yang menghasilkan sinyal masukan bagi masing-masing MOSFET pada blok inverter, sehingga proses pensaklaran pada rangkaian inverter dapat berjalan.
- Diagram blok controller berisi rangkaian kendali Proportional Integral Derivative (PID) yang disusun dengan tiga buah gain, masing-masing gain berfungsi sebagai masukan nilai proportional (Kp), integral (Ki) dan derivative (Kd).

# Simulasi Driver Motor BLDC digunakan dalam perencanaan driver motor BLDC agar dapat menghasilkan kecepatan putar (rpm) yang stabil saat terjadi perubahan beban torsi. Rangkaian kendali PID digunakan untuk memperoleh respon transien dengan nilai lonjakan yang rendah.
