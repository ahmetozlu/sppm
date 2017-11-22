# SPEM
The Smart Phone Energy Meter (SPEM) hardware provide a robust energy measurement solution for mobile devices. It can analyze the energy on any device that uses up to a Lithium-Ion Battery. Electrical engineers and software developers can utilize the SPEM hardware to optimize the design and analyze the performance of their mobile devices. For technical details check the related [medium post](https://medium.com/@ahmetozlu93/designing-and-developing-smartphone-power-monitor-hardware-61eb5a3ee0ce). 

## Quick Demo
<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/33150104-2e833bbc-cfe3-11e7-9fe1-ac044e8c0ef1.gif">
</p>

---
### Results

One of the experiment scenario;
- Screen brightness level is minimum.
- Smartphone is idle for first 2500 milliseconds.
- Download starts at 2500-2650 milliseconds.
- Chrome App for Android is started at 2650-2750 milliseconds.
- 200Mb data is started to download.
- After download completed, smartphone keeps idle from 4250 milliseconds to 6000 milliseconds.

The result of this experiment is given at below (both consumed power and mobile data rate).

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/33150206-87346b32-cfe3-11e7-9e79-1125709c6408.jpeg">
</p>

---

If you’re new to energy monitoring in the mobile design process, either when building mobile hardware or writing software-based applications, [this post](https://medium.com/@ahmetozlu93/designing-and-developing-smartphone-power-monitor-hardware-61eb5a3ee0ce) can point you in the right direction, helping you identify what characteristics to consider and developing your own power monitor hardware.

## Citation
If you use this code for your publications, please cite it as:

    @ONLINE{vdtc,
        author = "Ahmet Özlü",
        title  = "Smart Phone Power Monitor",
        year   = "2017",
        url    = "https://github.com/ahmetozlu/SPEM"
    }

## Author
Ahmet Özlü

## License
This system is available under the MIT license. See the LICENSE file for more info.
