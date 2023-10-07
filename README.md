# pytorch_env_test

## collect_env.py
文件来自```detectron2\detectron2\utils\```可以测试Pytorch环境
取出来后可以直接执行（但是可能需要额外安装一些里面用到的库）
执行后输出如下：
---------------------  -----------------------------------------------------------------------------------------------
sys.platform           win32
Python                 3.11.4 | packaged by Anaconda, Inc. | (main, Jul  5 2023, 13:47:18) [MSC v.1916 64 bit (AMD64)]
numpy                  1.26.0
detectron2             failed to import
detectron2._C          not built correctly: No module named 'detectron2'
DETECTRON2_ENV_MODULE  <not set>
PyTorch                2.1.0 @C:\ProgramData\miniconda3\Lib\site-packages\torch
PyTorch debug build    False
GPU available          False
Pillow                 10.0.1
torchvision            0.16.0 @C:\ProgramData\miniconda3\Lib\site-packages\torchvision
cv2                    4.8.0
---------------------  -----------------------------------------------------------------------------------------------
PyTorch built with:
  - C++ Version: 199711
  - MSVC 192930151
  - Intel(R) Math Kernel Library Version 2020.0.2 Product Build 20200624 for Intel(R) 64 architecture applications
  - Intel(R) MKL-DNN v3.1.1 (Git Hash 64f6bcbcbab628e96f33a62c3e975f8535a7bde4)
  - OpenMP 2019
  - LAPACK is enabled (usually provided by MKL)
  - CPU capability usage: AVX2
  - Build settings: BLAS_INFO=mkl, BUILD_TYPE=Release, CXX_COMPILER=C:/cb/pytorch_1000000000000/work/tmp_bin/sccache-cl.exe, CXX_FLAGS=/DWIN32 /D_WINDOWS /GR /EHsc /bigobj /FS -DUSE_PTHREADPOOL -DNDEBUG -DUSE_KINETO -DLIBKINETO_NOCUPTI -DLIBKINETO_NOROCTRACER -DUSE_FBGEMM -DUSE_XNNPACK -DSYMBOLICATE_MOBILE_DEBUG_HANDLE /utf-8 /wd4624 /wd4068 /wd4067 /wd4267 /wd4661 /wd4717 /wd4244 /wd4804 /wd4273, LAPACK_INFO=mkl, PERF_WITH_AVX=1, PERF_WITH_AVX2=1, PERF_WITH_AVX512=1, TORCH_DISABLE_GPU_ASSERTS=OFF, TORCH_VERSION=2.1.0, USE_CUDA=0, USE_CUDNN=OFF, USE_EXCEPTION_PTR=1, USE_GFLAGS=OFF, USE_GLOG=OFF, USE_MKL=ON, USE_MKLDNN=ON, USE_MPI=OFF, USE_NCCL=OFF, USE_NNPACK=OFF, USE_OPENMP=ON, USE_ROCM=OFF,
