# Marlin_2_0_SKR_Mini_E3_V1.2
Config marlin 2.0 for SKR mini E3 V1.2

Xem các tham số cần cấu hình https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/tree/master/firmware/V1.2

- Pin sử dụng nguồn 5V hay 12 Volt
![image](https://user-images.githubusercontent.com/38026441/69205737-6a45d380-0b7d-11ea-9527-2ce40efde5fd.png)
![image](https://user-images.githubusercontent.com/38026441/69206396-189e4880-0b7f-11ea-8a8d-a95b45afa871.png)
![image](https://user-images.githubusercontent.com/38026441/69208464-391dd100-0b86-11ea-8932-f54fedf9b405.png)
![SKR_E3_Mini_1 2_wiring](https://user-images.githubusercontent.com/38026441/69301910-5ddb7c80-0c4a-11ea-8e6a-9f1a90fbc6e9.png)


- Cấu hình firmware


![SKR mini E3 1.2](https://user-images.githubusercontent.com/25599056/60634053-0aee5d80-9e40-11e9-9658-7cac8b6d1002.png)

![SKR mini E3 1.2](https://user-images.githubusercontent.com/25599056/66630670-4a92c580-ec37-11e9-9c40-2d9f095ce4af.png)

![SKR mini E3 1.2](https://user-images.githubusercontent.com/25599056/66633694-fd662200-ec3d-11e9-9569-4c27f1123dc6.png)

![SKR mini E3 1.2](https://user-images.githubusercontent.com/25599056/67383650-22ee1680-f5c2-11e9-9009-8c6dc6308cf3.png)

![SKR mini E3 1.2](https://user-images.githubusercontent.com/25599056/66630522-0c95a180-ec37-11e9-9560-3c2b729b3310.png)

![SKR mini E3 1.2](https://user-images.githubusercontent.com/25599056/60634508-b0560100-9e41-11e9-9a3a-2fc217564a15.png)

![SKR mini E3 1.2](https://user-images.githubusercontent.com/25599056/60634579-ff9c3180-9e41-11e9-91aa-ae90dbbbdd3f.png)

NEED NOT modify the TMC2209 slave address, default 0 is ok!
comment out //#define SPEAKER, if you don't comment out this, it will freeze when you pressed button

![SKR mini E3 1.2](https://user-images.githubusercontent.com/25599056/61014965-6e3a3b80-a3bc-11e9-8035-6463a2757cd7.png)

if you enable BLTOUCH
Please enable #define FAN_SOFT_PWM too, if not the fan will modify servo control signal duty cycle 
    
![SKR mini E3 1.2](https://user-images.githubusercontent.com/25599056/66694083-95b5e280-ece2-11e9-819b-e2ae3a710a83.png)

