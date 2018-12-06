# minio-petabyte
Minio petabyte deployment for kubernetes, tested on v 1.10.11. this is a distributed deployment stategy.

32 pods with 4 drives each. Each drive 16 Tb.

2048 TB , using Minio formula (n/2) n=drives, it gives you 1024 TB or 1 Pb of space.
