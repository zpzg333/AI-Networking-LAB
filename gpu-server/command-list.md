===== nvidia-smi --query-gpu=index,name,temperature.gpu,memory.used --format=csv =====
index, name, temperature.gpu, memory.used [MiB]

* nvida-smi GPU 상태 조회
* Query-gpu 뒤의 인자로 조회하고자 하는 요소를 결정

* 결과
0, NVIDIA B200, 31, 0 MiB => index(0번 GPU) / name(NVIDA B200) / 온도 / 메모리 사용양
1, NVIDIA B200, 37, 0 MiB
2, NVIDIA B200, 39, 0 MiB
3, NVIDIA B200, 31, 0 MiB
4, NVIDIA B200, 31, 0 MiB
5, NVIDIA B200, 39, 0 MiB
6, NVIDIA B200, 38, 0 MiB
7, NVIDIA B200, 31, 0 MiB
