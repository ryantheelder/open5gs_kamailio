# [VoLTE Setup](https://github.com/ryantheelder/open5gs_kamailio)

## Introduction
The following content is from [Ericsson](https://www.ericsson.com/en/volte). you can aslo read more in [Wikipedia](https://en.wikipedia.org/wiki/Voice_over_LTE).
### What is VoLTE?
VoLTE (voice over LTE) is the foundation for evolving mobile voice and communication services for packet switched 4G, Wi-Fi and 5G networks. It is the mainstream mobile network technology for enabling globally interoperable voice and communication services, using IP Multimedia Subsystem (IMS). VoLTE enables high-quality and seamless HD voice services across a multitude of devices like smartphones, smartwatches and enterprise end-points. IMS also enables 5G voice and communication services.

### What are the benefits of VoLTE?​



* VoLTE enables improved and innovative voice and communication services across smartphones, wearables, smart speakers, other devices and enterprise end-points over LTE, Wi-Fi and 5G networks​
* It provides a foundation for improving business and enterprise collaboration services in combination with high-quality mobile voice services​
* VoLTE provides telecom grade services for consumers, businesses, enterprises and industries and is deployed with cloud-based solutions ​


## Tested Setup
**Host Machine:**
```console
foo@bar:~$ lsb_release -a
Distributor ID: Ubuntu
Description:    Ubuntu 18.04.6 LTS
Release:        18.04
Codename:       bionic
```
**Software Defined Radio (SDR)**:

[Ettus USRP B210](https://www.ettus.com/all-products/ub210-kit/): No clock is used.
