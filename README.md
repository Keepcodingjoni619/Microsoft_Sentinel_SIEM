# Microsoft_Sentinel_SIEM

<h3>Objective</h3>
<ul>
  <li>Create Virtual Machine/Resource Group</li>
  <li>Configure Port Rules</li>
  <li>Set Up Microsoft Sentinel</li>
</ul>

<h3>Description</h3>
<p>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third-party API to collect geographic information about the attackers' location.</p>
<p>he script is used in this demo where I set up Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to Look up the attackers' Geolocation information and plot it on an Azure Sentinel Map!</p>

<h3>Languages Used</h3>
<ul>
  <li>Powershell: Extracted RDP failed logon logs from Window Event Viewer</li>
</ul>
<h3>Utilities User</h3>
<ul>
  <li>ipgeolocation.io: IP Address to Geolocation API</li>
</ul>


![SIEM_01](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/e84aaa7e-b394-430b-b43e-2a5cda1a10ff)

![SIEM_02](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/69427626-ee13-4b19-82d5-932cd65be1e0)

![SIEM_03](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/d11698a5-cf31-4230-b0c6-31cdf85d900f)

![SIEM_04](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/ee29dd6d-cc4a-4dc5-8722-81974d20795e)

![SIEM_05](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/93790a2c-7521-4814-adc7-d1314aa752a0)

![SIEM_06](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/535bb335-ab26-446f-a151-f36c00c204aa)

![SIEM_07](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/7e794575-ebe2-4b9f-8d77-a1399c933cc6)

![SIEM_08](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/45aea347-5510-4164-9ce0-9d06795b6dca)

![SIEM_09](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/06f38ffa-8767-427d-aa3b-800fb6bec769)

![SIEM_11](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/da171803-3e34-44bc-a561-c524a9656bbe)

![SIEM_12](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/0ffcd156-b942-4dc3-92fd-9d0c1f4aef10)

![SIEM_13](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/22fc49f3-a86f-4909-8ee1-83e958e9db97)

![SIEM_14](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/b13499ad-ce74-43d9-8a6c-bfb933dd84cd)

![SIEM_15](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/47fba8d1-7df0-4fbb-920d-0fa2849c5328)

![SIEM_16](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/59cec1b9-e791-4578-a3d9-4e27190cdc83)

![SIEM_17](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/794d1fc1-6fa6-4bd4-a09d-3782a936dea0)

![SIEM_18](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/1318d79a-6dc4-4bd2-9043-35d3badc98ac)

![SIEM_19](https://github.com/Keepcodingjoni619/Microsoft_Sentinel_SIEM/assets/82996237/f93a46e3-b0d1-46df-9fbc-7fe560fef7e0)

