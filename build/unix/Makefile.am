warningflags = -Wall -Wextra -Wno-unused-parameter -Wno-missing-field-initializers -Wshadow
includeflags = -I$(srcdir)/../../src
commonflags = -O3 $(MFLAGS) $(warningflags) $(includeflags)
AM_CXXFLAGS = -std=c++11 $(commonflags)

lib_LTLIBRARIES = libfmtconv.la

libfmtconv_la_SOURCES = ../../src/avstp.h \
                        ../../src/AvstpWrapper.cpp \
                        ../../src/AvstpWrapper.h \
                        ../../src/main.cpp \
                        ../../src/types.h \
                        ../../src/VapourSynth.h \
                        ../../src/conc/AioAdd.h \
                        ../../src/conc/AioAdd.hpp \
                        ../../src/conc/AioMax.h \
                        ../../src/conc/AioMax.hpp \
                        ../../src/conc/AioSub.h \
                        ../../src/conc/AioSub.hpp \
                        ../../src/conc/Array.h \
                        ../../src/conc/Array.hpp \
                        ../../src/conc/AtomicInt.h \
                        ../../src/conc/AtomicInt.hpp \
                        ../../src/conc/AtomicIntOp.h \
                        ../../src/conc/AtomicIntOp.hpp \
                        ../../src/conc/AtomicMem.h \
                        ../../src/conc/AtomicMem.hpp \
                        ../../src/conc/AtomicPtr.h \
                        ../../src/conc/AtomicPtr.hpp \
                        ../../src/conc/AtomicPtrIntPair.h \
                        ../../src/conc/AtomicPtrIntPair.hpp \
                        ../../src/conc/CellPool.h \
                        ../../src/conc/CellPool.hpp \
                        ../../src/conc/def.h \
                        ../../src/conc/fnc.h \
                        ../../src/conc/fnc.hpp \
                        ../../src/conc/Interlocked.h \
                        ../../src/conc/Interlocked.hpp \
                        ../../src/conc/LockFreeCell.h \
                        ../../src/conc/LockFreeQueue.h \
                        ../../src/conc/LockFreeQueue.hpp \
                        ../../src/conc/LockFreeStack.h \
                        ../../src/conc/LockFreeStack.hpp \
                        ../../src/conc/ObjFactoryDef.h \
                        ../../src/conc/ObjFactoryDef.hpp \
                        ../../src/conc/ObjFactoryInterface.h \
                        ../../src/conc/ObjFactoryInterface.hpp \
                        ../../src/conc/ObjPool.h \
                        ../../src/conc/ObjPool.hpp \
                        ../../src/ffft/def.h \
                        ../../src/ffft/DynArray.h \
                        ../../src/ffft/DynArray.hpp \
                        ../../src/ffft/FFTReal.h \
                        ../../src/ffft/FFTReal.hpp \
                        ../../src/ffft/OscSinCos.h \
                        ../../src/ffft/OscSinCos.hpp \
                        ../../src/fmtc/ArrayAlign.h \
                        ../../src/fmtc/ArrayAlign.hpp \
                        ../../src/fmtc/Bitdepth.cpp \
                        ../../src/fmtc/Bitdepth.h \
                        ../../src/fmtc/Convert.cpp \
                        ../../src/fmtc/Convert.h \
                        ../../src/fmtc/ConvStep.cpp \
                        ../../src/fmtc/ConvStep.h \
                        ../../src/fmtc/Matrix2020CL.cpp \
                        ../../src/fmtc/Matrix2020CL.h \
                        ../../src/fmtc/Matrix.cpp \
                        ../../src/fmtc/Matrix.h \
                        ../../src/fmtc/NativeToStack16.cpp \
                        ../../src/fmtc/NativeToStack16.h \
                        ../../src/fmtc/Resample.cpp \
                        ../../src/fmtc/Resample.h \
                        ../../src/fmtc/SplFmtUtl.h \
                        ../../src/fmtc/SplFmtUtl.hpp \
                        ../../src/fmtc/Stack16ToNative.cpp \
                        ../../src/fmtc/Stack16ToNative.h \
                        ../../src/fmtc/Transfer.cpp \
                        ../../src/fmtc/Transfer.h \
                        ../../src/fmtc/Transfer.hpp \
                        ../../src/fmtc/version.h \
                        ../../src/fmtcl/BitBltConv.cpp \
                        ../../src/fmtcl/BitBltConv.h \
                        ../../src/fmtcl/ChromaPlacement.cpp \
                        ../../src/fmtcl/ChromaPlacement.h \
                        ../../src/fmtcl/CoefArrInt.cpp \
                        ../../src/fmtcl/CoefArrInt.h \
                        ../../src/fmtcl/CoefArrInt.hpp \
                        ../../src/fmtcl/ColorSpaceH265.h \
                        ../../src/fmtcl/ContFirBlackman.cpp \
                        ../../src/fmtcl/ContFirBlackman.h \
                        ../../src/fmtcl/ContFirBlackmanMinLobe.cpp \
                        ../../src/fmtcl/ContFirBlackmanMinLobe.h \
                        ../../src/fmtcl/ContFirCubic.cpp \
                        ../../src/fmtcl/ContFirCubic.h \
                        ../../src/fmtcl/ContFirFromDiscrete.cpp \
                        ../../src/fmtcl/ContFirFromDiscrete.h \
                        ../../src/fmtcl/ContFirGauss.cpp \
                        ../../src/fmtcl/ContFirGauss.h \
                        ../../src/fmtcl/ContFirInterface.cpp \
                        ../../src/fmtcl/ContFirInterface.h \
                        ../../src/fmtcl/ContFirLanczos.cpp \
                        ../../src/fmtcl/ContFirLanczos.h \
                        ../../src/fmtcl/ContFirLinear.cpp \
                        ../../src/fmtcl/ContFirLinear.h \
                        ../../src/fmtcl/ContFirRect.cpp \
                        ../../src/fmtcl/ContFirRect.h \
                        ../../src/fmtcl/ContFirSinc.cpp \
                        ../../src/fmtcl/ContFirSinc.h \
                        ../../src/fmtcl/ContFirSnh.cpp \
                        ../../src/fmtcl/ContFirSnh.h \
                        ../../src/fmtcl/ContFirSpline16.cpp \
                        ../../src/fmtcl/ContFirSpline16.h \
                        ../../src/fmtcl/ContFirSpline36.cpp \
                        ../../src/fmtcl/ContFirSpline36.h \
                        ../../src/fmtcl/ContFirSpline64.cpp \
                        ../../src/fmtcl/ContFirSpline64.h \
                        ../../src/fmtcl/ContFirSpline.cpp \
                        ../../src/fmtcl/ContFirSpline.h \
                        ../../src/fmtcl/DiscreteFirCustom.cpp \
                        ../../src/fmtcl/DiscreteFirCustom.h \
                        ../../src/fmtcl/DiscreteFirInterface.cpp \
                        ../../src/fmtcl/DiscreteFirInterface.h \
                        ../../src/fmtcl/ErrDifBuf.cpp \
                        ../../src/fmtcl/ErrDifBuf.h \
                        ../../src/fmtcl/ErrDifBuf.hpp \
                        ../../src/fmtcl/ErrDifBufFactory.cpp \
                        ../../src/fmtcl/ErrDifBufFactory.h \
                        ../../src/fmtcl/FilterResize.cpp \
                        ../../src/fmtcl/FilterResize.h \
                        ../../src/fmtcl/KernelData.cpp \
                        ../../src/fmtcl/KernelData.h \
                        ../../src/fmtcl/Proxy.h \
                        ../../src/fmtcl/Proxy.hpp \
                        ../../src/fmtcl/ProxyRwCpp.h \
                        ../../src/fmtcl/ProxyRwCpp.hpp \
                        ../../src/fmtcl/ProxyRwSse2.h \
                        ../../src/fmtcl/ProxyRwSse2.hpp \
                        ../../src/fmtcl/ResampleSpecPlane.cpp \
                        ../../src/fmtcl/ResampleSpecPlane.h \
                        ../../src/fmtcl/ResizeData.cpp \
                        ../../src/fmtcl/ResizeData.h \
                        ../../src/fmtcl/ResizeData.hpp \
                        ../../src/fmtcl/ResizeDataFactory.cpp \
                        ../../src/fmtcl/ResizeDataFactory.h \
                        ../../src/fmtcl/Scaler.cpp \
                        ../../src/fmtcl/Scaler.h \
                        ../../src/fmtcl/Scaler.hpp \
                        ../../src/fmtcl/ScalerCopy.h \
                        ../../src/fmtcl/SplFmt.h \
                        ../../src/fmtcl/SplFmt.hpp \
                        ../../src/fmtcl/TransCurve.h \
                        ../../src/fstb/AllocAlign.h \
                        ../../src/fstb/AllocAlign.hpp \
                        ../../src/fstb/CpuId.cpp \
                        ../../src/fstb/CpuId.h \
                        ../../src/fstb/def.h \
                        ../../src/fstb/fnc.cpp \
                        ../../src/fstb/fnc.h \
                        ../../src/fstb/fnc.hpp \
                        ../../src/fstb/ToolsSse2.cpp \
                        ../../src/fstb/ToolsSse2.h \
                        ../../src/fstb/ToolsSse2.hpp \
                        ../../src/vsutl/CpuOpt.cpp \
                        ../../src/vsutl/CpuOpt.h \
                        ../../src/vsutl/FilterBase.cpp \
                        ../../src/vsutl/FilterBase.h \
                        ../../src/vsutl/fnc.cpp \
                        ../../src/vsutl/fnc.h \
                        ../../src/vsutl/FrameRefSPtr.h \
                        ../../src/vsutl/FuncRefSPtr.h \
                        ../../src/vsutl/NodeRefSPtr.h \
                        ../../src/vsutl/ObjRefSPtr.h \
                        ../../src/vsutl/ObjRefSPtr.hpp \
                        ../../src/vsutl/PlaneProcCbInterface.cpp \
                        ../../src/vsutl/PlaneProcCbInterface.h \
                        ../../src/vsutl/PlaneProcessor.cpp \
                        ../../src/vsutl/PlaneProcessor.h \
                        ../../src/vsutl/PlaneProcMode.h \
                        ../../src/vsutl/Redirect.h \
                        ../../src/vsutl/Redirect.hpp

libfmtconv_la_LDFLAGS = -no-undefined -avoid-version $(PLUGINLDFLAGS)


noinst_LTLIBRARIES = libavx2.la

libavx2_la_SOURCES = ../../src/fmtcl/BitBltConv_avx2.cpp \
                     ../../src/fmtcl/ProxyRwAvx2.h \
                     ../../src/fmtcl/ProxyRwAvx2.hpp \
                     ../../src/fmtcl/Scaler_avx2.cpp \
                     ../../src/fmtc/Matrix_avx2.cpp \
                     ../../src/fmtc/Transfer_avx2.cpp \
                     ../../src/fstb/ToolsAvx2.cpp \
                     ../../src/fstb/ToolsAvx2.h \
                     ../../src/fstb/ToolsAvx2.hpp

libavx2_la_CXXFLAGS = $(AM_CXXFLAGS) -mavx2


libfmtconv_la_LIBADD = libavx2.la
