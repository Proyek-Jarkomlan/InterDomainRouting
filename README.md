# 📄 **Inter Domain Routing**

## **Configuration**

![Inter Domain Routing Configuration](https://github.com/Proyek-Jarkomlan/InterDomainRouting/blob/main/assets/Inter%20Domain%20Routing.jpg?raw=true)

## **Steps**
1. Clone this repository:
   ```bash
   git clone https://github.com/Proyek-Jarkomlan/InterDomainRouting.git
2. Navigate directory to the project:
   ```bash
   cd InterDomainRouting
3. Run the project for scenario one with this command:
   ```bash
   sudo python3 bgp-lab.py -c frr-config-scenario1
4. Run this command to test the project:

   **Notes: We apologize that this step cannot be executed because the frr.conf that we have set locally, cannot be saved and configured. You can test it by trying to configure it manually according to the configuration that we have done.**
   ```bash
   C1_1 traceroute -n C3_1
6. Exit from the terminal and start for scenario two with this command:
   ```bash
   sudo python3 bgp-lab.py -c frr-config-scenario2
7. Run this command to test the project:

   **Notes: We apologize that this step cannot be executed because the frr.conf that we have set locally, cannot be saved and configured. You can test it by trying to configure it manually according to the configuration that we have done.**
   ```bash
   C1_1 traceroute -n C2_1
   C1_1 traceroute -n C3_1
9. If you have successfully traceroute, the project is successful.
