# Read alignment 

## Background 

# Install bowtie2

 ```
wget https://sourceforge.net/projects/bowtie-bio/files/bowtie2/2.3.4.3/bowtie2-2.3.4.3-linux-x86_64.zip
unzip bowtie2-2.3.4.3-macos-x86_64.zip
```
In case you don't have wget command installed. Please use the following commannds

```
1. Open https://sourceforge.net/projects/bowtie-bio/files/latest/download
2. This will download bowtie zip file in the Download directory
3. run this command : mv ~/Download/bowtie* ./
or just cop manually from the Download directory 
```




- Install bowtie2, download latest version from here 

```
./bowtie2-2.3.4.3-macos-x86_64/bowtie2 -x ./bowtie2-2.3.4.3-macos-x86_64/example/index/lambda_virus -U reads.toy.example.fastq  >reads.toy.example.sam
```

- Unzip BWA using this command: 

```
unzip bowtie2-2.3.4.3-macos-x86_64.zip
```
- Run bowtie2 using the following command 

```
./bowtie2-2.3.4.3-macos-x86_64/bowtie2 -x ./bowtie2-2.3.4.3-macos-x86_64/example/index/lambda_virus -U reads.toy.example.fastq  >reads.toy.example.sam
```

