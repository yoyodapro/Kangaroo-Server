# Kangaroo-Server

This is a privately run Kangaroo server for cracking bitcoin private keys related to the 32 BTC transaction puzzle: https://bitcointalk.org/index.php?topic=1306983.0

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Please join our Discord server for updates on progress. https://discord.gg/DjMksx8wqr

If you do not join the discord, please use your preffered BTC address as your username on your worker client. otherwise you will not be credited for work once the address is found
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
To run please download the Git as a zip file, extract both files to the same folder. YOU WILL need to modify the workerserver.bat file before you begin.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Kangaroo v2.1 (Build by JeanLucPons)

please only make your changes to this portion of the bat file: [-t 0 -gpu -gpuId 0,1 -w yourusername]

-t [Number of CPU threads] ex. -t 1 will run one thread, 0 for no threads

-gpu [Enables GPU Calculation]

-gpuId [Enables specific GPU's] ex. -gpuId 0,1,2,3,4,5,6,7 will run 8 GPU's

-w [your worker ID or Bitcoin Address if you prefer to remain anonymous] if using multiple rigs please use -w username.rignumber
