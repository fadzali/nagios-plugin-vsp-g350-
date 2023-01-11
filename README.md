<a name="readme-top"></a>
<h3 align="center">NAGIOS-PLUGIN-VSP-G350</h3>

## Usage

1. DKU Status
   ```sh
   snmpwalk -v 2c -c xxxx iphot .1.3.6.1.4.1.116.5.11.4.1.1.7
   ```
2. DKC status
   ```sh
   snmpwalk -v 2c -c xxxx iphost .1.3.6.1.4.1.116.5.11.4.1.1.6.1
   ```
3. Information 
   ```sh
   snmpwalk -v 2c -c xxxx -On iphost .1.3.6.1
   ```
## Output

  <a href="https://user-images.githubusercontent.com/3030238/211696376-a1c62f47-6a30-4d66-9076-2c485a6826f1.pnge">
    <img src="https://user-images.githubusercontent.com/3030238/211696376-a1c62f47-6a30-4d66-9076-2c485a6826f1.png">
  </a>

## Refs
1. https://www.storageinfra.com/hitachi-virtual-storage-platform-vsp-architecture/
2. http://www.oidview.com/mibs/116/HDS9900MIB.html
<p align="right">(<a href="#readme-top">back to top</a>)</p>
