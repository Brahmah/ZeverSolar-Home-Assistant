# ZeverSolar-Home-Assistant
Query's Data From ZeverSolar Inverters Locally Without Using ZeverCloud

## Setup

1. Give your inverter a static IP that your Home Assistant install can access
2. Replace `<zeversolar_ip_here>` with the IP of your inverter in [ZeverSolar.yaml](https://github.com/TomW1605/ZeverSolar-Home-Assistant/blob/master/ZeverSolar.yaml)
3. Either copy the contents of [ZeverSolar.yaml](https://github.com/TomW1605/ZeverSolar-Home-Assistant/blob/master/ZeverSolar.yaml) into your local `configuration.yaml` or reference it from there
4. Copy the contents of [configuration.yaml](https://github.com/TomW1605/ZeverSolar-Home-Assistant/blob/master/configuration.yaml) into your local `configuration.yaml`
5. (Optional) you can remove either or both of the state/error sensors if you do not need them.
