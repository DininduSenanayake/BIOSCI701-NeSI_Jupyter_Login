# Troubleshooting

## `Invalid response: 503 Service Unavailable` 

If we attempt to open a large file such as **.fastq** file via Jupyter file explorer by double clicking it (especially with session running **4GB** of memory), Jupyter session will exhaust the amount of the memory and trigger `Invalid response: 503 Service Unavailable` (similar to below)

<center>
![image](./images/503_serviceunavailable.png){width="500"}
</center>

!!! success "Solution"

    * Click   <KBD>File</KBD> **>** <KBD>Hub Control Panel</KBD> from Jupyter Menu
    * Click <KBD>Step My Server</KBD> and then <KBD>Start My Server</KBD>
    * Open a new server session with **4cpus** and **16GB** of memory (or **32GB** but 16 should be enough)

<center>