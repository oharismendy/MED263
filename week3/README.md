# Week 3. Exploring Raw NGS Data (Olivier Harismendy)



### Docker

1. Install Docker

2. Choose and change to a working directory in your host computer (your laptop computer in most cases).

3. Please download and extract materials and recource data in [Zip file](https://ucsdcloud-my.sharepoint.com/:u:/g/personal/j5kim_ucsd_edu/EXR69n7AktVGuR3Gb0Oo_SMBYUWoPWYS5ZQpqOEMxKGyCQ) to your working directory.

4. Start running docker by typing following command in Terminal (macOS/Linux) or Anaconda Prompt (Windows). Replace `/Users/johndoe/mylocalfolder` with your workding directory in your local/host computer (=laptop computer).
```bash
docker run -it -v /Users/johndoe/mylocalfolder:/work j5kim/med263-harismendy
```


### IGV 