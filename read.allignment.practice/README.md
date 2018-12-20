# Read alignment 

Tools needed
- bowtie2,  

- Reference genome and reads are available here
- https://github.com/QCB-Collaboratory/W1.UNIX.command.line/tree/master/read.allignment.practice



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

