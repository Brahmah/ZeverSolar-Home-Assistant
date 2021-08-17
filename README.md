# ZeverSolar-Home-Assistant
Query's Data From ZeverSolar Inverters Locally Without Using ZeverCloud

## Setup

1. Give your inverter a static IP that your Home Assistant install can access
2. Either copy the contents of [ZeverSolar.yaml](https://github.com/TomW1605/ZeverSolar-Home-Assistant/blob/master/ZeverSolar.yaml) into your local `configuration.yaml` or reference it from there
3. Replace `<zeversolar_ip_here>` with the IP of your inverter in [ZeverSolar.yaml](https://github.com/TomW1605/ZeverSolar-Home-Assistant/blob/master/ZeverSolar.yaml)
5. Copy the contents of [configuration.yaml](https://github.com/TomW1605/ZeverSolar-Home-Assistant/blob/master/configuration.yaml) into your local `configuration.yaml`
6. Replace the `+08:00` in [configuration.yaml](https://github.com/TomW1605/ZeverSolar-Home-Assistant/blob/master/configuration.yaml) with your local time zone offset from UTC
7. (Optional) you can remove either or both of the state/error sensors if you do not need them.
