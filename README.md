{"app_name":"MobilePhone","timestamp":"2019-11-26 00:57:53.17 -0600","app_version":"36","slice_uuid":"6b0fe5ac-ad31-3af7-9a63-b1d98191c0b3","adam_id":0,"build_version":"36","bundleID":"com.apple.mobilephone","share_with_app_devs":true,"is_first_party":true,"bug_type":"109","os_version":"iPhone OS 12.4.1 (16G102)","incident_id":"2FF13C7B-E4FC-46DD-AF5E-1D7EF087C6E0","name":"MobilePhone"}
Incident Identifier: 2FF13C7B-E4FC-46DD-AF5E-1D7EF087C6E0
CrashReporter Key:   36aa65d203cc53e6d9dfa9d1d55ee370525f482f
Hardware Model:      iPhone8,1
Process:             MobilePhone [3028]
Path:                /Applications/MobilePhone.app/MobilePhone
Identifier:          com.apple.mobilephone
Version:             36 (36)
Code Type:           ARM-64 (Native)
Role:                Non UI
Parent Process:      launchd [1]
Coalition:           com.apple.mobilephone [799]


Date/Time:           2019-11-26 00:57:53.0350 -0600
Launch Time:         2019-11-26 00:54:39.3401 -0600
OS Version:          iPhone OS 12.4.1 (16G102)
Baseband Version:    5.70.01
Report Version:      104

Exception Type:  EXC_CRASH (SIGABRT)
Exception Codes: 0x0000000000000000, 0x0000000000000000
Exception Note:  EXC_CORPSE_NOTIFY
Triggered by Thread:  3

Application Specific Information:
abort() called

Last Exception Backtrace:
(0x190f0a98c 0x1900e39f8 0x190e843f8 0x190e0940c 0x19bde9378 0x1a42af660 0x191943a9c 0x1a42af5e4 0x190948a38 0x1909497d4 0x1908f2324 0x1908f2e40 0x1908fb4ac 0x190b2a114 0x190b2ccd4)

Thread 0 name:  Dispatch queue: com.apple.main-thread
Thread 0:
0   libsystem_kernel.dylib        	0x0000000190a9c0f4 0x190a84000 + 98548
1   libsystem_kernel.dylib        	0x0000000190a9b5a0 0x190a84000 + 95648
2   CoreFoundation                	0x0000000190e9c120 0x190df2000 + 696608
3   CoreFoundation                	0x0000000190e97030 0x190df2000 + 675888
4   CoreFoundation                	0x0000000190e967c0 0x190df2000 + 673728
5   GraphicsServices              	0x000000019309779c 0x19308d000 + 42908
6   UIKitCore                     	0x00000001bd81bc38 0x1bcf5f000 + 9161784
7   MobilePhone                   	0x00000001020b9dbc 0x1020b8000 + 7612
8   libdyld.dylib                 	0x000000019095a8e0 0x190959000 + 6368

Thread 1 name:  com.apple.uikit.eventfetch-thread
Thread 1:
0   libsystem_kernel.dylib        	0x0000000190a9c0f4 0x190a84000 + 98548
1   libsystem_kernel.dylib        	0x0000000190a9b5a0 0x190a84000 + 95648
2   CoreFoundation                	0x0000000190e9c120 0x190df2000 + 696608
3   CoreFoundation                	0x0000000190e97030 0x190df2000 + 675888
4   CoreFoundation                	0x0000000190e967c0 0x190df2000 + 673728
5   Foundation                    	0x000000019186498c 0x19185d000 + 31116
6   Foundation                    	0x000000019186481c 0x19185d000 + 30748
7   UIKitCore                     	0x00000001bd901754 0x1bcf5f000 + 10102612
8   Foundation                    	0x00000001919914a0 0x19185d000 + 1262752
9   libsystem_pthread.dylib       	0x0000000190b292c0 0x190b1e000 + 45760
10  libsystem_pthread.dylib       	0x0000000190b29220 0x190b1e000 + 45600
11  libsystem_pthread.dylib       	0x0000000190b2ccdc 0x190b1e000 + 60636

Thread 2 name:  NetworkLoad
Thread 2:
0   libsystem_kernel.dylib        	0x0000000190a9c0f4 0x190a84000 + 98548
1   libsystem_kernel.dylib        	0x0000000190a9b5a0 0x190a84000 + 95648
2   CoreFoundation                	0x0000000190e9c120 0x190df2000 + 696608
3   CoreFoundation                	0x0000000190e97030 0x190df2000 + 675888
4   CoreFoundation                	0x0000000190e967c0 0x190df2000 + 673728
5   GeoServices                   	0x0000000197711c04 0x197133000 + 6155268
6   libsystem_pthread.dylib       	0x0000000190b292c0 0x190b1e000 + 45760
7   libsystem_pthread.dylib       	0x0000000190b29220 0x190b1e000 + 45600
8   libsystem_pthread.dylib       	0x0000000190b2ccdc 0x190b1e000 + 60636

Thread 3 name:  Dispatch queue: com.apple.TelephonyUI.TPFavoritesController.serialDispatchQueue
Thread 3 Crashed:
0   libsystem_kernel.dylib        	0x0000000190aa70dc 0x190a84000 + 143580
1   libsystem_pthread.dylib       	0x0000000190b20094 0x190b1e000 + 8340
2   libsystem_c.dylib             	0x00000001909ffea8 0x1909a5000 + 372392
3   libc++abi.dylib               	0x00000001900cc788 0x1900cb000 + 6024
4   libc++abi.dylib               	0x00000001900cc934 0x1900cb000 + 6452
5   libobjc.A.dylib               	0x00000001900e3e00 0x1900de000 + 24064
6   libc++abi.dylib               	0x00000001900d8838 0x1900cb000 + 55352
7   libc++abi.dylib               	0x00000001900d88c4 0x1900cb000 + 55492
8   libdispatch.dylib             	0x00000001909497e8 0x1908e9000 + 395240
9   libdispatch.dylib             	0x00000001908f2324 0x1908e9000 + 37668
10  libdispatch.dylib             	0x00000001908f2e40 0x1908e9000 + 40512
11  libdispatch.dylib             	0x00000001908fb4ac 0x1908e9000 + 74924
12  libsystem_pthread.dylib       	0x0000000190b2a114 0x190b1e000 + 49428
13  libsystem_pthread.dylib       	0x0000000190b2ccd4 0x190b1e000 + 60628

Thread 4:
0   libsystem_pthread.dylib       	0x0000000190b2ccd0 0x190b1e000 + 60624

Thread 3 crashed with ARM Thread State (64-bit):
    x0: 0x0000000000000000   x1: 0x0000000000000000   x2: 0x0000000000000000   x3: 0x00000002805153b7
    x4: 0x00000001900dbb71   x5: 0x000000016de5a460   x6: 0x000000000000006e   x7: 0xffffffffffffffec
    x8: 0x0000000000000c00   x9: 0x0000000190b24888  x10: 0x0000000190b1ff18  x11: 0x0000000000000003
   x12: 0x0000000000000000  x13: 0x0000000000000001  x14: 0x0000000000000010  x15: 0x0000000000000022
   x16: 0x0000000000000148  x17: 0x0000000000000000  x18: 0x0000000000000000  x19: 0x0000000000000006
   x20: 0x000000016de5b000  x21: 0x000000016de5a460  x22: 0x0000000000027a17  x23: 0x000000016de5b0e0
   x24: 0x0000000283e9ed40  x25: 0x0000000000000000  x26: 0x0000000000000000  x27: 0x0000000000000000
   x28: 0x000000016de5b0e0   fp: 0x000000016de5a3c0   lr: 0x0000000190b20094
    sp: 0x000000016de5a390   pc: 0x0000000190aa70dc cpsr: 0x00000000

Binary Images:
0x1020b8000 - 0x1021bbfff MobilePhone arm64  <6b0fe5acad313af79a63b1d98191c0b3> /Applications/MobilePhone.app/MobilePhone
0x102334000 - 0x10233ffff libobjc-trampolines.dylib arm64  <065bd8006d513c358dc14e2a8ff1ba31> /usr/lib/libobjc-trampolines.dylib
0x102358000 - 0x1023affff dyld arm64  <3049bf50a9b1318c8b2b34774de49438> /usr/lib/dyld
0x190073000 - 0x190074fff libSystem.B.dylib arm64  <7334f9562e353bfebf99f16d2589464a> /usr/lib/libSystem.B.dylib
0x190075000 - 0x1900cafff libc++.1.dylib arm64  <6a272068f00d37a984e331ba58e1c3c4> /usr/lib/libc++.1.dylib
0x1900cb000 - 0x1900ddfff libc++abi.dylib arm64  <d4920e50788d3be6bccf8f550bc6d491> /usr/lib/libc++abi.dylib
0x1900de000 - 0x190865fff libobjc.A.dylib arm64  <1167a03d9f853f34a96fd96818ad77b5> /usr/lib/libobjc.A.dylib
0x190866000 - 0x19086afff libcache.dylib arm64  <bd876f73c3ff39459113c6fa56d15e3d> /usr/lib/system/libcache.dylib
0x19086b000 - 0x190876fff libcommonCrypto.dylib arm64  <b6d7765a17a93ff4a095ee57139d16c5> /usr/lib/system/libcommonCrypto.dylib
0x190877000 - 0x19087bfff libcompiler_rt.dylib arm64  <644550d26c693e95affb4ce0b8c5c7a6> /usr/lib/system/libcompiler_rt.dylib
0x19087c000 - 0x190884fff libcopyfile.dylib arm64  <b0e27f378641392a9db65b4b002b959f> /usr/lib/system/libcopyfile.dylib
0x190885000 - 0x1908e8fff libcorecrypto.dylib arm64  <322648cea1933b92969887dee477d005> /usr/lib/system/libcorecrypto.dylib
0x1908e9000 - 0x190958fff libdispatch.dylib arm64  <c3d9e9a5b56e3215aed59b6affc80d91> /usr/lib/system/libdispatch.dylib
0x190959000 - 0x190982fff libdyld.dylib arm64  <5e181e9004763f7ba24dc51d73effd19> /usr/lib/system/libdyld.dylib
0x190983000 - 0x190983fff liblaunch.dylib arm64  <3569886aaa6a3576ab9a34935c16b079> /usr/lib/system/liblaunch.dylib
0x190984000 - 0x190989fff libmacho.dylib arm64  <9ce10d14bcb43369b0e85c4480010a66> /usr/lib/system/libmacho.dylib
0x19098a000 - 0x19098bfff libremovefile.dylib arm64  <268d6d12fe1030d5ba4607c5c467566c> /usr/lib/system/libremovefile.dylib
0x19098c000 - 0x1909a3fff libsystem_asl.dylib arm64  <d7a79215dca137388e9746226003b15b> /usr/lib/system/libsystem_asl.dylib
0x1909a4000 - 0x1909a4fff libsystem_blocks.dylib arm64  <a1405ce6ae42332e9a2e06d75041f6fe> /usr/lib/system/libsystem_blocks.dylib
0x1909a5000 - 0x190a26fff libsystem_c.dylib arm64  <fc4c83bb09133b92919b277e2b0d0ba7> /usr/lib/system/libsystem_c.dylib
0x190a27000 - 0x190a2bfff libsystem_configuration.dylib arm64  <218dc6f3496a3e37bcd497e824e727dc> /usr/lib/system/libsystem_configuration.dylib
0x190a2c000 - 0x190a33fff libsystem_containermanager.dylib arm64  <75002eacacfa3fbfbd6fb8699be042ee> /usr/lib/system/libsystem_containermanager.dylib
0x190a34000 - 0x190a35fff libsystem_coreservices.dylib arm64  <78c2250959bd387994b64a9e75464f58> /usr/lib/system/libsystem_coreservices.dylib
0x190a36000 - 0x190a3cfff libsystem_darwin.dylib arm64  <7e76bd3057d7373696850709fc7af50c> /usr/lib/system/libsystem_darwin.dylib
0x190a3d000 - 0x190a43fff libsystem_dnssd.dylib arm64  <d0e49be195bc3a07b2383c56dd2945ef> /usr/lib/system/libsystem_dnssd.dylib
0x190a44000 - 0x190a83fff libsystem_info.dylib arm64  <01aa4acd261b3fd8acf15150220161c9> /usr/lib/system/libsystem_info.dylib
0x190a84000 - 0x190aaefff libsystem_kernel.dylib arm64  <451947374fc437afa258be0e4593163a> /usr/lib/system/libsystem_kernel.dylib
0x190aaf000 - 0x190adcfff libsystem_m.dylib arm64  <e079abc4989b343b9fca3f43540cca7a> /usr/lib/system/libsystem_m.dylib
0x190add000 - 0x190afffff libsystem_malloc.dylib arm64  <8a218797621a36c6843dd862510c1d5c> /usr/lib/system/libsystem_malloc.dylib
0x190b00000 - 0x190b0bfff libsystem_networkextension.dylib arm64  <0193b597e65e3996890277ebd82cfc4d> /usr/lib/system/libsystem_networkextension.dylib
0x190b0c000 - 0x190b12fff libsystem_notify.dylib arm64  <b701e7f441c4356b88dc2ec865084c5f> /usr/lib/system/libsystem_notify.dylib
0x190b13000 - 0x190b1dfff libsystem_platform.dylib arm64  <c580957483993c36bae1caedb9184a78> /usr/lib/system/libsystem_platform.dylib
0x190b1e000 - 0x190b2efff libsystem_pthread.dylib arm64  <7dc8076100ab3c07ba487f82aae5dbe4> /usr/lib/system/libsystem_pthread.dylib
0x190b2f000 - 0x190b31fff libsystem_sandbox.dylib arm64  <fb9e8e7d1c9334d8a5b22b5212a324d1> /usr/lib/system/libsystem_sandbox.dylib
0x190b32000 - 0x190b39fff libsystem_symptoms.dylib arm64  <20d9b3659cea33c7956aa8545dee52a2> /usr/lib/system/libsystem_symptoms.dylib
0x190b3a000 - 0x190b4ffff libsystem_trace.dylib arm64  <9ac8424153f9310dbf99cfe4a6487434> /usr/lib/system/libsystem_trace.dylib
0x190b50000 - 0x190b55fff libunwind.dylib arm64  <df28d357cdc737d7ace356c0de492da3> /usr/lib/system/libunwind.dylib
0x190b56000 - 0x190b83fff libxpc.dylib arm64  <31e6baa6561f38e486d41d3b7527682b> /usr/lib/system/libxpc.dylib
0x190b84000 - 0x190ddffff libicucore.A.dylib arm64  <bcee3941878a3c96b7156502bfc4a15a> /usr/lib/libicucore.A.dylib
0x190de0000 - 0x190df1fff libz.1.dylib arm64  <206dc0d369803553ba987d4938299866> /usr/lib/libz.1.dylib
0x190df2000 - 0x19114ffff CoreFoundation arm64  <9a052c0830b6363babf2062f0b867758> /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
0x191150000 - 0x191160fff libbsm.0.dylib arm64  <97ae12002bcc30f59cd9f56bb48744a2> /usr/lib/libbsm.0.dylib
0x191161000 - 0x191161fff libenergytrace.dylib arm64  <21032416108a3e078b08e500bf8feec5> /usr/lib/libenergytrace.dylib
0x191162000 - 0x1911f0fff IOKit arm64  <26df71f60f253aa5bdeb374f1f70396c> /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
0x1911f1000 - 0x1912d8fff libxml2.2.dylib arm64  <09c6266beeb235038cc627672de28a1e> /usr/lib/libxml2.2.dylib
0x1912d9000 - 0x1912e6fff libbz2.1.0.dylib arm64  <ab9eb1272eee3d658a66bb3eddf951de> /usr/lib/libbz2.1.0.dylib
0x1912e7000 - 0x1912fffff liblzma.5.dylib arm64  <29538dbe21cd34ac8328b0f708ac58ac> /usr/lib/liblzma.5.dylib
0x191300000 - 0x191479fff libsqlite3.dylib arm64  <12c83eaeddbd3ef5965272236da869d5> /usr/lib/libsqlite3.dylib
0x19147a000 - 0x1914aefff libMobileGestalt.dylib arm64  <af3a9ec8e5dc3a7ea34974cc40f1769c> /usr/lib/libMobileGestalt.dylib
0x1914af000 - 0x19185cfff CFNetwork arm64  <d160964071a233529369006ee750fa0d> /System/Library/Frameworks/CFNetwork.framework/CFNetwork
0x19185d000 - 0x191b47fff Foundation arm64  <7a676a573fa63763a203969875bfaac3> /System/Library/Frameworks/Foundation.framework/Foundation
0x191b48000 - 0x191c56fff Security arm64  <549552bf5b7e3961918dd9a2b2f84b54> /System/Library/Frameworks/Security.framework/Security
0x191c57000 - 0x191cc0fff SystemConfiguration arm64  <0fc44d7afb97324b898a3880b94e27b5> /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration
0x191cc1000 - 0x191cf3fff libCRFSuite.dylib arm64  <e0b9971a4a58372c917e172262a230da> /usr/lib/libCRFSuite.dylib
0x191cf4000 - 0x191d0afff libapple_nghttp2.dylib arm64  <c878057f1a743813aad7651fcc833a1a> /usr/lib/libapple_nghttp2.dylib
0x191d0b000 - 0x191d34fff libarchive.2.dylib arm64  <65ec51aef94b3a1987332731a4d7c752> /usr/lib/libarchive.2.dylib
0x191d35000 - 0x191dfcfff libboringssl.dylib arm64  <380ed83911013ba8b0f37e5308129655> /usr/lib/libboringssl.dylib
0x191dfd000 - 0x191e13fff libcoretls.dylib arm64  <6b1e9bffa372352b878c7b1744ac4905> /usr/lib/libcoretls.dylib
0x191e14000 - 0x191e15fff libcoretls_cfhelpers.dylib arm64  <59609c5520313c6794b8930d3e648ecc> /usr/lib/libcoretls_cfhelpers.dylib
0x191e16000 - 0x191e17fff liblangid.dylib arm64  <0169f9e003833f25b07aeaed83704b74> /usr/lib/liblangid.dylib
0x191e18000 - 0x192188fff libnetwork.dylib arm64  <8a707f96087e36b8a1f7be4092e803d9> /usr/lib/libnetwork.dylib
0x192189000 - 0x1921bcfff libpcap.A.dylib arm64  <4fe6f38ffed23388a4621898ddb8be04> /usr/lib/libpcap.A.dylib
0x1921bd000 - 0x19221afff libusrtcp.dylib arm64  <8817d9115b5e3a61bb6030cd9b213b1c> /usr/lib/libusrtcp.dylib
0x19221b000 - 0x192227fff IOSurface arm64  <26ea7fabea43332792609476fbbff95b> /System/Library/Frameworks/IOSurface.framework/IOSurface
0x192228000 - 0x1922dafff libBLAS.dylib arm64  <5f5dc29a267c3ce089501fcdf56fa585> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBLAS.dylib
0x1922db000 - 0x1925f7fff libLAPACK.dylib arm64  <78d98e587d763e1d8c0e1694bf4eaf35> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libLAPACK.dylib
0x1925f8000 - 0x192866fff vImage arm64  <78052afe98c83c3ba2101bd84c4c7d03> /System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/vImage
0x192867000 - 0x192878fff libSparseBLAS.dylib arm64  <19f40e7928d33f37b2954c0c0736392e> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libSparseBLAS.dylib
0x192879000 - 0x1928d3fff libvMisc.dylib arm64  <e2588d2c24b2325daa45167a1d52978b> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libvMisc.dylib
0x1928d4000 - 0x192902fff libBNNS.dylib arm64  <575133594b483c3db8e58473a9477e51> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBNNS.dylib
0x192903000 - 0x192917fff libLinearAlgebra.dylib arm64  <d3c7b6714b533000966bf9b8fb2ea578> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libLinearAlgebra.dylib
0x192918000 - 0x19291cfff libQuadrature.dylib arm64  <c3ba9791c2f13a139a32d3476406f371> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libQuadrature.dylib
0x19291d000 - 0x19298bfff libSparse.dylib arm64  <998dcddd9c0a396d946e3bcb56ae9fa4> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libSparse.dylib
0x19298c000 - 0x192a1cfff libvDSP.dylib arm64  <91bc58b57f7d367d9b94a5a8db4f9e6a> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libvDSP.dylib
0x192a1d000 - 0x192a1dfff vecLib arm64  <3764dc7f15ff3782b899b8b66578b591> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/vecLib
0x192a1e000 - 0x192a1efff Accelerate arm64  <89ca8b5b6a31367685d10baca08c6927> /System/Library/Frameworks/Accelerate.framework/Accelerate
0x192a1f000 - 0x192a36fff libcompression.dylib arm64  <b3be8cb0e428337db977e92f8b64a999> /usr/lib/libcompression.dylib
0x192a37000 - 0x192fdbfff CoreGraphics arm64  <f25c45eceaeb36a9a2ee82bfbff7adc7> /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
0x192fdc000 - 0x192fe1fff IOAccelerator arm64  <f38e5eb385c332c6b05d8f591d41c000> /System/Library/PrivateFrameworks/IOAccelerator.framework/IOAccelerator
0x192fe2000 - 0x192fe7fff libCoreFSCache.dylib arm64  <85e629c6c4e73b6693a297ef7d1d852d> /System/Library/Frameworks/OpenGLES.framework/libCoreFSCache.dylib
0x192fe8000 - 0x19308cfff Metal arm64  <2f3a24f09c7032d59e5181642fed20f2> /System/Library/Frameworks/Metal.framework/Metal
0x19308d000 - 0x19309ffff GraphicsServices arm64  <5dc71f1e2db03637b0517c9574dd609e> /System/Library/PrivateFrameworks/GraphicsServices.framework/GraphicsServices
0x1930a0000 - 0x1930a0fff MobileCoreServices arm64  <106d91760a3834338e483f4c208c8e16> /System/Library/Frameworks/MobileCoreServices.framework/MobileCoreServices
0x1930a1000 - 0x1930a3fff IOSurfaceAccelerator arm64  <3a58f6c1af6b3fec8df682bd9608a3cd> /System/Library/PrivateFrameworks/IOSurfaceAccelerator.framework/IOSurfaceAccelerator
0x1930a4000 - 0x1930e6fff AppleJPEG arm64  <c4ff6005434534dcaae115264c7b9bf5> /System/Library/PrivateFrameworks/AppleJPEG.framework/AppleJPEG
0x1930e7000 - 0x193683fff ImageIO arm64  <79a0ce8581283b619226e5e088522dcf> /System/Library/Frameworks/ImageIO.framework/ImageIO
0x193684000 - 0x1936f2fff BaseBoard arm64  <badf69222b6b33d6a5860e8eaad4c96b> /System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard
0x1936f3000 - 0x193708fff AssertionServices arm64  <0168c4ca3f5b3fa0b3d265ac72c61105> /System/Library/PrivateFrameworks/AssertionServices.framework/AssertionServices
0x193709000 - 0x193711fff CorePhoneNumbers arm64  <b742b09e53d13fc0907dfe0dfc809860> /System/Library/PrivateFrameworks/CorePhoneNumbers.framework/CorePhoneNumbers
0x193712000 - 0x193755fff AppSupport arm64  <b600f93045b83de4a90273eceff10460> /System/Library/PrivateFrameworks/AppSupport.framework/AppSupport
0x193756000 - 0x19376efff CrashReporterSupport arm64  <af147e857db630f88bae47b476084948> /System/Library/PrivateFrameworks/CrashReporterSupport.framework/CrashReporterSupport
0x19376f000 - 0x193774fff AggregateDictionary arm64  <9d0819342e9839c485df24e5ac4bd33f> /System/Library/PrivateFrameworks/AggregateDictionary.framework/AggregateDictionary
0x193775000 - 0x1937f0fff libTelephonyUtilDynamic.dylib arm64  <434b9743c7e6367ab83d589f87f30a94> /usr/lib/libTelephonyUtilDynamic.dylib
0x1937f1000 - 0x19380ffff ProtocolBuffer arm64  <8b3396ec22843e69b43e959e35cfc899> /System/Library/PrivateFrameworks/ProtocolBuffer.framework/ProtocolBuffer
0x193810000 - 0x19383ffff MobileKeyBag arm64  <fadc4125d47f376eb07ff210d2ef93b8> /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag
0x193840000 - 0x19387afff BackBoardServices arm64  <a473a297d27531b096eda139b1a2f311> /System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices
0x19387b000 - 0x1938ddfff FrontBoardServices arm64  <4ee9cc7aee25390f8979b51873a9cfc8> /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices
0x1938de000 - 0x193923fff SpringBoardServices arm64  <acc01c8480013712a275bfdd77372059> /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices
0x193924000 - 0x193937fff PowerLog arm64  <76c8314f28f33bf1bf03c6740e630ba1> /System/Library/PrivateFrameworks/PowerLog.framework/PowerLog
0x193938000 - 0x193952fff CommonUtilities arm64  <5aee46a5ee843787badaeeded4921f29> /System/Library/PrivateFrameworks/CommonUtilities.framework/CommonUtilities
0x193953000 - 0x19395efff liblockdown.dylib arm64  <d3ca6a6e2d253541825fd95c67b93536> /usr/lib/liblockdown.dylib
0x19395f000 - 0x193c81fff CoreData arm64  <c2943249821a32a6aadd24f2c19d8110> /System/Library/Frameworks/CoreData.framework/CoreData
0x193c82000 - 0x193c89fff TCC arm64  <0bf6f96fc35630d78f570de780afbfe1> /System/Library/PrivateFrameworks/TCC.framework/TCC
0x193c8a000 - 0x193c91fff libcupolicy.dylib arm64  <784b482538eb3463b5b41990f73ad637> /usr/lib/libcupolicy.dylib
0x193c92000 - 0x193d65fff CoreTelephony arm64  <a903cd022d0b3d459dac8d7de3bcbf58> /System/Library/Frameworks/CoreTelephony.framework/CoreTelephony
0x193d66000 - 0x193dbdfff Accounts arm64  <c3eae3e92f9e3d0bb7566db5965bb8eb> /System/Library/Frameworks/Accounts.framework/Accounts
0x193dbe000 - 0x193de1fff AppleSauce arm64  <1041d29a89963b1292f9e6d1e2fca9ca> /System/Library/PrivateFrameworks/AppleSauce.framework/AppleSauce
0x193de2000 - 0x193decfff DataMigration arm64  <7e7e6c0b4b8a3848aa39be2a253bbedf> /System/Library/PrivateFrameworks/DataMigration.framework/DataMigration
0x193ded000 - 0x193df3fff Netrb arm64  <54b90ecfd7c93e2f8bb87e53c5f1d2bb> /System/Library/PrivateFrameworks/Netrb.framework/Netrb
0x193df4000 - 0x193e25fff PersistentConnection arm64  <0ab4107d070b3206b677a4d0772177cc> /System/Library/PrivateFrameworks/PersistentConnection.framework/PersistentConnection
0x193e26000 - 0x193e36fff libmis.dylib arm64  <d297888a7a3b3d6f8655ce89c54de06c> /usr/lib/libmis.dylib
0x193e37000 - 0x193f3cfff ManagedConfiguration arm64  <c8f976f051ff31ca8ae71d0851815090> /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration
0x193f3d000 - 0x193f42fff libReverseProxyDevice.dylib arm64  <034e4becec3637049836b6f5c4206438> /usr/lib/libReverseProxyDevice.dylib
0x193f43000 - 0x193f55fff libamsupport.dylib arm64  <4f0fe9ba7ca231508bb33887e9fe4de0> /usr/lib/libamsupport.dylib
0x193f56000 - 0x193f5bfff libCoreVMClient.dylib arm64  <bdfd156fdbac3b29bd3b9edc444b3eb4> /System/Library/Frameworks/OpenGLES.framework/libCoreVMClient.dylib
0x193f5c000 - 0x193f5dfff libCVMSPluginSupport.dylib arm64  <c0fc3e49d71b3163bf201bc108cc1a90> /System/Library/Frameworks/OpenGLES.framework/libCVMSPluginSupport.dylib
0x193f5e000 - 0x193f61fff libutil.dylib arm64  <2c7f8b771c2a3e17b9886a1a23c1d8e6> /usr/lib/libutil.dylib
0x193f62000 - 0x193f9ffff libGLImage.dylib arm64  <2ad83e8c080c357da6a2330acf3072ac> /System/Library/Frameworks/OpenGLES.framework/libGLImage.dylib
0x193fa0000 - 0x19401dfff APFS arm64  <ad14f1dd819f3ec69672be6ea36d7cb1> /System/Library/PrivateFrameworks/APFS.framework/APFS
0x19401e000 - 0x19404ffff MediaKit arm64  <badad9be1cfc33c88995c641384b0ee5> /System/Library/PrivateFrameworks/MediaKit.framework/MediaKit
0x194050000 - 0x19406afff libSERestoreInfo.dylib arm64  <04f883333cf831e4a41d9a52420e9ac4> /usr/lib/updaters/libSERestoreInfo.dylib
0x194071000 - 0x1940acfff DiskImages arm64  <47dfcedb4d943af58a8ef2f705d2e72e> /System/Library/PrivateFrameworks/DiskImages.framework/DiskImages
0x1940ad000 - 0x1940b6fff libGFXShared.dylib arm64  <4ff1edf0a77838f18b219b35dfe083d5> /System/Library/Frameworks/OpenGLES.framework/libGFXShared.dylib
0x1940b7000 - 0x194104fff libauthinstall.dylib arm64  <f6b951d33eae37efbb0f286e1d5b843b> /usr/lib/libauthinstall.dylib
0x194105000 - 0x19410dfff IOMobileFramebuffer arm64  <be858d7b2da33fd88f7b2b7e53bd5ad1> /System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/IOMobileFramebuffer
0x19410e000 - 0x194118fff OpenGLES arm64  <9f8abef1a049321f9d57ca5cda4a2f00> /System/Library/Frameworks/OpenGLES.framework/OpenGLES
0x194119000 - 0x194239fff ColorSync arm64  <9e1bc6fa2b653b75a9a3b54a5556cbb4> /System/Library/PrivateFrameworks/ColorSync.framework/ColorSync
0x19423a000 - 0x194269fff CoreVideo arm64  <34ae98df7545385c927e737be5d7a522> /System/Library/Frameworks/CoreVideo.framework/CoreVideo
0x19426a000 - 0x19426bfff libCTGreenTeaLogger.dylib arm64  <c37cb5afb3763316b09a121faafd1f9f> /usr/lib/libCTGreenTeaLogger.dylib
0x19426c000 - 0x1943bdfff CoreAudio arm64  <d4b1d5f994c939e4b62644d63b354570> /System/Library/Frameworks/CoreAudio.framework/CoreAudio
0x1943be000 - 0x1943ddfff CoreAnalytics arm64  <e546eb30c7ea3914ab1e27cafe7be4e7> /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics
0x1943de000 - 0x1943e1fff UserFS arm64  <67b2206977d33d718428f764e22f1c1f> /System/Library/PrivateFrameworks/UserFS.framework/UserFS
0x1943e2000 - 0x194596fff CoreMedia arm64  <3eac09db9ff43791aff296aa884f7838> /System/Library/Frameworks/CoreMedia.framework/CoreMedia
0x194597000 - 0x1945a9fff libprotobuf-lite.dylib arm64  <5a7d2aefbf0f3397a810de4052e6dec1> /usr/lib/libprotobuf-lite.dylib
0x1945aa000 - 0x194607fff libprotobuf.dylib arm64  <1250be912c8230099d3ad358caae3138> /usr/lib/libprotobuf.dylib
0x194608000 - 0x194925fff libAWDSupportFramework.dylib arm64  <9a9d3540d2f33c86b9c48683e1ad17a6> /usr/lib/libAWDSupportFramework.dylib
0x194926000 - 0x19496bfff WirelessDiagnostics arm64  <d013da9df515350e908e98e7440094e8> /System/Library/PrivateFrameworks/WirelessDiagnostics.framework/WirelessDiagnostics
0x19496c000 - 0x194a2cfff VideoToolbox arm64  <f9404bbaa2003e988110de61fa03e0c2> /System/Library/Frameworks/VideoToolbox.framework/VideoToolbox
0x194a2d000 - 0x194b31fff libFontParser.dylib arm64  <598fa684304938c59b619ec516296960> /System/Library/PrivateFrameworks/FontServices.framework/libFontParser.dylib
0x194b32000 - 0x194b32fff FontServices arm64  <118619dde6f031008a4c88b3e59fb602> /System/Library/PrivateFrameworks/FontServices.framework/FontServices
0x194b33000 - 0x194c94fff CoreText arm64  <1f2c7269a1c833179923ebc381ba2b74> /System/Library/Frameworks/CoreText.framework/CoreText
0x194c95000 - 0x194ca3fff IntlPreferences arm64  <60dad887158631308fabef459231bc32> /System/Library/PrivateFrameworks/IntlPreferences.framework/IntlPreferences
0x194ca4000 - 0x194cadfff RTCReporting arm64  <627a5bfd20243637b88ef2de819615e7> /System/Library/PrivateFrameworks/RTCReporting.framework/RTCReporting
0x194cae000 - 0x194d5ffff CoreBrightness arm64  <6a07d919568e30caa815a07a35c759b1> /System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness
0x194d60000 - 0x194d69fff libAudioStatistics.dylib arm64  <0ee8779e8f46351ab5e2d1ff920527d3> /usr/lib/libAudioStatistics.dylib
0x194d6a000 - 0x195308fff AudioToolbox arm64  <de9300e2a2833438b1eeb0d1084d3f28> /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox
0x195309000 - 0x195542fff QuartzCore arm64  <dcc3316ad07f32faa3f377368ba2629d> /System/Library/Frameworks/QuartzCore.framework/QuartzCore
0x195543000 - 0x19554dfff MediaAccessibility arm64  <cc82138dbb093d219bd3a2718ab30a9e> /System/Library/Frameworks/MediaAccessibility.framework/MediaAccessibility
0x19554e000 - 0x195640fff libiconv.2.dylib arm64  <56a508dc6e3132c38a3e58b1c7e272b9> /usr/lib/libiconv.2.dylib
0x195641000 - 0x19565cfff NetworkStatistics arm64  <3c50de03a9a737b588f12853a14e96b1> /System/Library/PrivateFrameworks/NetworkStatistics.framework/NetworkStatistics
0x19565d000 - 0x19567bfff MPSCore arm64  <6a931631e0ac3c04bb516c0988308f4a> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSCore.framework/MPSCore
0x19567c000 - 0x1956effff MPSImage arm64  <b087e4ccc88633bb9ea72a488b9f4777> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSImage.framework/MPSImage
0x1956f0000 - 0x195714fff MPSMatrix arm64  <29df73ac8b283336a59f6bfea2a1e359> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSMatrix.framework/MPSMatrix
0x195715000 - 0x195723fff CoreAUC arm64  <d8391c59fa3430e9b3d3ffe25d5da657> /System/Library/PrivateFrameworks/CoreAUC.framework/CoreAUC
0x195724000 - 0x195db1fff MediaToolbox arm64  <8fef31551d783b26847087f147672adc> /System/Library/Frameworks/MediaToolbox.framework/MediaToolbox
0x195db2000 - 0x195f1cfff MPSNeuralNetwork arm64  <755d418ed5c83ff399bc31e3d6332ea0> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNeuralNetwork.framework/MPSNeuralNetwork
0x195f1d000 - 0x195f1dfff MetalPerformanceShaders arm64  <d1f20d7ab61634d5a8fbe8755f2040eb> /System/Library/Frameworks/MetalPerformanceShaders.framework/MetalPerformanceShaders
0x195f1e000 - 0x196330fff FaceCore arm64  <aab6e9fba0ab34598e0fdc6659f7da83> /System/Library/PrivateFrameworks/FaceCore.framework/FaceCore
0x196331000 - 0x19633efff GraphVisualizer arm64  <2d52616bba7034d3b796e28dd3ac28dd> /System/Library/PrivateFrameworks/GraphVisualizer.framework/GraphVisualizer
0x19633f000 - 0x196563fff libFosl_dynamic.dylib arm64  <9a8eb9eab7bd3569888a0eec5e08e111> /usr/lib/libFosl_dynamic.dylib
0x196564000 - 0x1967f8fff CoreImage arm64  <74c3a439c3ad3274a7749cb933c6e530> /System/Library/Frameworks/CoreImage.framework/CoreImage
0x1967f9000 - 0x196a1bfff CoreMotion arm64  <00ca957a89e136e883ebfb7a213a84f2> /System/Library/Frameworks/CoreMotion.framework/CoreMotion
0x196a1c000 - 0x196a4afff CoreBluetooth arm64  <092e5de73f713593aacded1e15865d5e> /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
0x196a4b000 - 0x196a6cfff PlugInKit arm64  <eabcfbf1fa9e36bbb50c8b453f8d0e3c> /System/Library/PrivateFrameworks/PlugInKit.framework/PlugInKit
0x196a6d000 - 0x196cf9fff Celestial arm64  <c37a342a731e35718ed26dd4e196b7fc> /System/Library/PrivateFrameworks/Celestial.framework/Celestial
0x196cfa000 - 0x196d7bfff Quagga arm64  <6d1eaf0f42e2362bae5bdaebad5b8aef> /System/Library/PrivateFrameworks/Quagga.framework/Quagga
0x196d7c000 - 0x196e72fff AVFAudio arm64  <943ab4d1d6363303ac591636a41af0e7> /System/Library/Frameworks/AVFoundation.framework/Frameworks/AVFAudio.framework/AVFAudio
0x196e73000 - 0x19706ffff AVFoundation arm64  <a81613f7b8c23340a6e66889b754dff2> /System/Library/Frameworks/AVFoundation.framework/AVFoundation
0x197070000 - 0x19708dfff CacheDelete arm64  <dbcb92cf51b13e5d93cc7e4b39f3c5a7> /System/Library/PrivateFrameworks/CacheDelete.framework/CacheDelete
0x19708e000 - 0x1970c7fff StreamingZip arm64  <7a4bacc4a03b32678f537466a08c9545> /System/Library/PrivateFrameworks/StreamingZip.framework/StreamingZip
0x1970c8000 - 0x1970dafff CoreEmoji arm64  <3176564260083593a577fddfebcfe966> /System/Library/PrivateFrameworks/CoreEmoji.framework/CoreEmoji
0x1970db000 - 0x19712afff CoreLocationProtobuf arm64  <5a17ecbb765d313da64c3dd317cdf36e> /System/Library/PrivateFrameworks/CoreLocationProtobuf.framework/CoreLocationProtobuf
0x19712b000 - 0x197132fff SymptomDiagnosticReporter arm64  <6769718294d532db8a0fcfbc574943fc> /System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter
0x197133000 - 0x197b1afff GeoServices arm64  <54b6c1595a653969a7bf582e299138e0> /System/Library/PrivateFrameworks/GeoServices.framework/GeoServices
0x197b1b000 - 0x197b35fff MobileAsset arm64  <005d5c2d4b9232a696ce0fb6a08a38d1> /System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset
0x197b36000 - 0x197b71fff Lexicon arm64  <933886c128ce34a0be4c8819ac295671> /System/Library/PrivateFrameworks/Lexicon.framework/Lexicon
0x197b72000 - 0x197b83fff libcmph.dylib arm64  <a29f078d192a3820a97f13612890b828> /usr/lib/libcmph.dylib
0x197b84000 - 0x197c93fff LanguageModeling arm64  <8b351556f38436b1bd0ded1df086f21f> /System/Library/PrivateFrameworks/LanguageModeling.framework/LanguageModeling
0x197cab000 - 0x197d45fff CoreLocation arm64  <8a4743559e13333ca8370d273843c57c> /System/Library/Frameworks/CoreLocation.framework/CoreLocation
0x197d46000 - 0x197d46fff PhoneNumbers arm64  <d9c422c80d413a2f97518a502f46bf27> /System/Library/PrivateFrameworks/PhoneNumbers.framework/PhoneNumbers
0x197d47000 - 0x197d51fff libChineseTokenizer.dylib arm64  <efcf77f0c6e5377abecb6182f6f255fa> /usr/lib/libChineseTokenizer.dylib
0x197d52000 - 0x197e02fff libmecab_em.dylib arm64  <dda9fda7a8453bf38c8ead5ef703a539> /usr/lib/libmecab_em.dylib
0x197e03000 - 0x197e04fff libThaiTokenizer.dylib arm64  <c2426d11f4853443a8fe06d2ddd39c23> /usr/lib/libThaiTokenizer.dylib
0x197e05000 - 0x197e09fff libgermantok.dylib arm64  <5df65797933b3f8eb4de5fb0d8e0fb23> /usr/lib/libgermantok.dylib
0x197e0a000 - 0x197e6dfff CoreNLP arm64  <f839dd5f26483b2f9737c13e972d3cd4> /System/Library/PrivateFrameworks/CoreNLP.framework/CoreNLP
0x197e7a000 - 0x19803efff MobileSpotlightIndex arm64  <4ce2ef8e5bba3f279c4bbacabf2774bc> /System/Library/PrivateFrameworks/MobileSpotlightIndex.framework/MobileSpotlightIndex
0x19803f000 - 0x1980a0fff CoreSpotlight arm64  <e5421d2a8cf934e9a8047e9762679c64> /System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight
0x1980a1000 - 0x198d40fff JavaScriptCore arm64  <ff70546036c53d9a872e85627c2dd077> /System/Library/Frameworks/JavaScriptCore.framework/JavaScriptCore
0x198d41000 - 0x198d46fff libheimdal-asn1.dylib arm64  <a001ff6596873832a6e8dbd55cbd855a> /usr/lib/libheimdal-asn1.dylib
0x198d47000 - 0x198dc1fff libate.dylib arm64  <4108470b5bec3d6d822dc9238b091e87> /usr/lib/libate.dylib
0x198dc2000 - 0x198e69fff TextureIO arm64  <63bd61765abd313891e0f0ddc4989f3f> /System/Library/PrivateFrameworks/TextureIO.framework/TextureIO
0x198e6a000 - 0x198f2dfff CoreUI arm64  <5a57278bb4d4357a90c7750917924edd> /System/Library/PrivateFrameworks/CoreUI.framework/CoreUI
0x198f2e000 - 0x198f3bfff MobileIcons arm64  <23be50d2eccb3e0a87efb2b27eb8fdfa> /System/Library/PrivateFrameworks/MobileIcons.framework/MobileIcons
0x198f3c000 - 0x198f4afff AppleFSCompression arm64  <8235503d9da135edad1eee984726d760> /System/Library/PrivateFrameworks/AppleFSCompression.framework/AppleFSCompression
0x198f4b000 - 0x198fb3fff TextInput arm64  <01d2e7c0c6a03b988dad4c1ee1826eeb> /System/Library/PrivateFrameworks/TextInput.framework/TextInput
0x198fdd000 - 0x199010fff DataDetectorsCore arm64  <d876d8aaf1b938388c287b4a669ed62e> /System/Library/PrivateFrameworks/DataDetectorsCore.framework/DataDetectorsCore
0x199011000 - 0x1990a2fff FileProvider arm64  <6423940f8d023c9cabffc444e9973eab> /System/Library/Frameworks/FileProvider.framework/FileProvider
0x1990a3000 - 0x199198fff NLP arm64  <531e2b7f020a38c2b08f2fda174e63b7> /System/Library/PrivateFrameworks/NLP.framework/NLP
0x199199000 - 0x19926efff ProofReader arm64  <f509810086b03f4b873eac19a93676a6> /System/Library/PrivateFrameworks/ProofReader.framework/ProofReader
0x19926f000 - 0x199284fff libAccessibility.dylib arm64  <4299a46ac44b3a8b968963062d682d52> /usr/lib/libAccessibility.dylib
0x199285000 - 0x199772fff libwebrtc.dylib arm64  <723c13ece1a1393cba5f52348f0a9124> /System/Library/PrivateFrameworks/WebCore.framework/Frameworks/libwebrtc.dylib
0x199773000 - 0x1997d7fff ContactsFoundation arm64  <8e400dcb974732cf9d54a03e13861749> /System/Library/PrivateFrameworks/ContactsFoundation.framework/ContactsFoundation
0x1997d8000 - 0x19b136fff WebCore arm64  <79d4f140d81b32a8a8813a5198c6ae8b> /System/Library/PrivateFrameworks/WebCore.framework/WebCore
0x19b137000 - 0x19b2d0fff WebKitLegacy arm64  <faf611b319243f4fb0da0d86d333abe7> /System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy
0x19b2d1000 - 0x19b300fff DataAccessExpress arm64  <3a56283fa1fd31c688d4783d7d17ac53> /System/Library/PrivateFrameworks/DataAccessExpress.framework/DataAccessExpress
0x19b301000 - 0x19b39afff AddressBookLegacy arm64  <b728fecda6fa38f7a597680f64cb59c9> /System/Library/PrivateFrameworks/AddressBookLegacy.framework/AddressBookLegacy
0x19b39b000 - 0x19b3f2fff ProtectedCloudStorage arm64  <426539dbd6c63e7ea5f705e7f6458484> /System/Library/PrivateFrameworks/ProtectedCloudStorage.framework/ProtectedCloudStorage
0x19b3f3000 - 0x19b424fff UserNotifications arm64  <49419a6088123a1088967b389728a68f> /System/Library/Frameworks/UserNotifications.framework/UserNotifications
0x19b425000 - 0x19b430fff AppleIDAuthSupport arm64  <92fec1a8c8303bc4940f1b6edca15e68> /System/Library/PrivateFrameworks/AppleIDAuthSupport.framework/AppleIDAuthSupport
0x19b431000 - 0x19b486fff AuthKit arm64  <ceeb4570eb5938c0a212a07da5438fac> /System/Library/PrivateFrameworks/AuthKit.framework/AuthKit
0x19b4c5000 - 0x19b4c5fff UIKit arm64  <8cd1d805e6403980aacdef9414284c81> /System/Library/Frameworks/UIKit.framework/UIKit
0x19b4c6000 - 0x19b4d9fff DocumentManagerCore arm64  <1efaab5ea8633d4ca743c824e8521d8c> /System/Library/PrivateFrameworks/DocumentManagerCore.framework/DocumentManagerCore
0x19b4da000 - 0x19b4e8fff HangTracer arm64  <6ae4008081833ad286621b36839ef849> /System/Library/PrivateFrameworks/HangTracer.framework/HangTracer
0x19b4e9000 - 0x19b537fff PhysicsKit arm64  <361f88aa7ddb33d68c252f8d02c624ad> /System/Library/PrivateFrameworks/PhysicsKit.framework/PhysicsKit
0x19b538000 - 0x19b53cfff StudyLog arm64  <4c2f7de1107e3ce2b61e679fe40d466d> /System/Library/PrivateFrameworks/StudyLog.framework/StudyLog
0x19b53d000 - 0x19b628fff UIFoundation arm64  <77e12b7c184e344fb3511494c24d86be> /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation
0x19b629000 - 0x19b749fff CloudKit arm64  <a3e0d95652ea39daa6b5ef1bbf15288d> /System/Library/Frameworks/CloudKit.framework/CloudKit
0x19b74a000 - 0x19b751fff IntentsFoundation arm64  <11acb79008683e9a8222fbdf2f20af39> /System/Library/PrivateFrameworks/IntentsFoundation.framework/IntentsFoundation
0x19b752000 - 0x19ba38fff Intents arm64  <6ae5175fc6b03e919433a966c42c85ad> /System/Library/Frameworks/Intents.framework/Intents
0x19ba39000 - 0x19ba51fff libresolv.9.dylib arm64  <578816afe31737f7bff30011a1499be9> /usr/lib/libresolv.9.dylib
0x19ba52000 - 0x19ba54fff CoreDuetDebugLogging arm64  <ed6a80d9f48d33b994e978b91b1a4c32> /System/Library/PrivateFrameworks/CoreDuetDebugLogging.framework/CoreDuetDebugLogging
0x19ba55000 - 0x19ba86fff libtidy.A.dylib arm64  <2473e09a24e23441b5fa5adccce49c17> /usr/lib/libtidy.A.dylib
0x19ba87000 - 0x19bc41fff CoreDuet arm64  <59b9f0b87177312681f88367bfe3424f> /System/Library/PrivateFrameworks/CoreDuet.framework/CoreDuet
0x19bc42000 - 0x19bc62fff CoreDuetContext arm64  <1ec73f4da44d31b28d4c4371110202b1> /System/Library/PrivateFrameworks/CoreDuetContext.framework/CoreDuetContext
0x19bc63000 - 0x19bc74fff CoreDuetDaemonProtocol arm64  <2e09aa3473a4394eb6626641a0ea8842> /System/Library/PrivateFrameworks/CoreDuetDaemonProtocol.framework/CoreDuetDaemonProtocol
0x19bc75000 - 0x19bcdbfff IMFoundation arm64  <3e2cfc69dc12331a9df863027d3fa16a> /System/Library/PrivateFrameworks/IMFoundation.framework/IMFoundation
0x19bcdc000 - 0x19bd0dfff vCard arm64  <2816c3799d4c39238da9d7763eb8f66a> /System/Library/PrivateFrameworks/vCard.framework/vCard
0x19bd0e000 - 0x19be1ffff Contacts arm64  <1306c6d1be3d32318cfc2009f388c1ba> /System/Library/Frameworks/Contacts.framework/Contacts
0x19be20000 - 0x19be21fff DiagnosticLogCollection arm64  <1b7c22827b0839729399b4af14a4d536> /System/Library/PrivateFrameworks/DiagnosticLogCollection.framework/DiagnosticLogCollection
0x19be22000 - 0x19be23fff Marco arm64  <597764710750346a88f800ea9088b830> /System/Library/PrivateFrameworks/Marco.framework/Marco
0x19be24000 - 0x19be2bfff MessageProtection arm64  <e2f1b2ab571832429b93fa306244c251> /System/Library/PrivateFrameworks/MessageProtection.framework/MessageProtection
0x19be2c000 - 0x19c118fff StoreServices arm64  <2e8fa52212793a8290bc9ccba912ef79> /System/Library/PrivateFrameworks/StoreServices.framework/StoreServices
0x19c119000 - 0x19c12ffff Engram arm64  <55b36649e1033a3da75e792841d829a1> /System/Library/PrivateFrameworks/Engram.framework/Engram
0x19c130000 - 0x19c23ffff IDSFoundation arm64  <13cf42cace3d37d6a1402620b2d9e2e4> /System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation
0x19c240000 - 0x19c24afff CaptiveNetwork arm64  <6040b78e56283f4b8933a23497391977> /System/Library/PrivateFrameworks/CaptiveNetwork.framework/CaptiveNetwork
0x19c24b000 - 0x19c27afff EAP8021X arm64  <1e909550518531ae8e5af4f84ae81121> /System/Library/PrivateFrameworks/EAP8021X.framework/EAP8021X
0x19c27b000 - 0x19c2b8fff MobileWiFi arm64  <aaea4968329138e58544669798387a37> /System/Library/PrivateFrameworks/MobileWiFi.framework/MobileWiFi
0x19c2b9000 - 0x19c2bbfff OAuth arm64  <3159f643ab4f32198c5f2e0cf5e03efb> /System/Library/PrivateFrameworks/OAuth.framework/OAuth
0x19c2bc000 - 0x19c2befff CommonAuth arm64  <76aa4d5daeca34ef846373b4e163f258> /System/Library/PrivateFrameworks/CommonAuth.framework/CommonAuth
0x19c2bf000 - 0x19c32efff Heimdal arm64  <5627b7f99336377f83867e29a58382ba> /System/Library/PrivateFrameworks/Heimdal.framework/Heimdal
0x19c32f000 - 0x19c358fff GSS arm64  <4f5f9a56b6523d5e9b9fb3ecd20d1e2a> /System/Library/Frameworks/GSS.framework/GSS
0x19c359000 - 0x19c370fff ApplePushService arm64  <733176c26c2e361a844495297b4f5077> /System/Library/PrivateFrameworks/ApplePushService.framework/ApplePushService
0x19c371000 - 0x19c400fff AccountsDaemon arm64  <4dce3b079300348391f68bb0129e5e5c> /System/Library/PrivateFrameworks/AccountsDaemon.framework/AccountsDaemon
0x19c401000 - 0x19c422fff AppleIDSSOAuthentication arm64  <2feb9afa1d313d2fae112373362f6819> /System/Library/PrivateFrameworks/AppleIDSSOAuthentication.framework/AppleIDSSOAuthentication
0x19c423000 - 0x19c4a3fff AppleAccount arm64  <54af56912426303aa6ea2c8adfb0786d> /System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount
0x19c4a4000 - 0x19c61afff CoreUtils arm64  <db2fa88f45033e4d927583ceddaaa618> /System/Library/PrivateFrameworks/CoreUtils.framework/CoreUtils
0x19c61b000 - 0x19c714fff IDS arm64  <80abe1ba9c2d39b496ed3afe9879fdff> /System/Library/PrivateFrameworks/IDS.framework/IDS
0x19c715000 - 0x19c73bfff MediaServices arm64  <d29cf787e4f5359f8c91baa426a6d6fa> /System/Library/PrivateFrameworks/MediaServices.framework/MediaServices
0x19c73c000 - 0x19c90ffff MediaRemote arm64  <f2305c6b02c73b9fb4ff40fe5aab4855> /System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote
0x19c910000 - 0x19c92afff UserManagement arm64  <ef562d815d4b371b92a8de235544a85c> /System/Library/PrivateFrameworks/UserManagement.framework/UserManagement
0x19c93c000 - 0x19c96cfff Bom arm64  <1d3570dfb8b5353d9ca9434ac3d29648> /System/Library/PrivateFrameworks/Bom.framework/Bom
0x19c96d000 - 0x19c971fff CommunicationsFilter arm64  <476acf80b48938548194fa700571d6c6> /System/Library/PrivateFrameworks/CommunicationsFilter.framework/CommunicationsFilter
0x19c972000 - 0x19c992fff FTAWD arm64  <4e7bcdf2ed19377c81dc6bacb4e2b53f> /System/Library/PrivateFrameworks/FTAWD.framework/FTAWD
0x19c993000 - 0x19c9e8fff FTServices arm64  <ac072f2d230538038a0872bb654fb0cb> /System/Library/PrivateFrameworks/FTServices.framework/FTServices
0x19ca20000 - 0x19ca2bfff ProactiveEventTracker arm64  <2fe28b856dee36a18d352a569887408a> /System/Library/PrivateFrameworks/ProactiveEventTracker.framework/ProactiveEventTracker
0x19ca2c000 - 0x19ca7afff ChunkingLibrary arm64  <e9d985bdc95b33c6b8077c94754edc76> /System/Library/PrivateFrameworks/ChunkingLibrary.framework/ChunkingLibrary
0x19ca7b000 - 0x19ca89fff libnetworkextension.dylib arm64  <c588fd853b103e689968fa24a7496cb3> /usr/lib/libnetworkextension.dylib
0x19ca8a000 - 0x19caadfff AddressBook arm64  <5535c9f12e2e3aa880dd18af440b2c39> /System/Library/Frameworks/AddressBook.framework/AddressBook
0x19d807000 - 0x19d9a4fff NetworkExtension arm64  <ced5acebcbf835f3b5553a4910a70e25> /System/Library/Frameworks/NetworkExtension.framework/NetworkExtension
0x19d9a5000 - 0x19ddcffff SiriTTS arm64  <d89cb39bb2dc3a2a940baea589979e5f> /System/Library/PrivateFrameworks/SiriTTS.framework/SiriTTS
0x19ddd0000 - 0x19de2efff SAObjects arm64  <4ca04a3d2cc53ca78fda0f00e54f4f62> /System/Library/PrivateFrameworks/SAObjects.framework/SAObjects
0x19de2f000 - 0x19de6efff VoiceServices arm64  <4494d60a2c673a5e8bea57c4cbe7d437> /System/Library/PrivateFrameworks/VoiceServices.framework/VoiceServices
0x19de9e000 - 0x19dfc7fff AssistantServices arm64  <7273ad96f5e1303cae5ad962bd14e9ca> /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices
0x19dfc8000 - 0x19dfe5fff AssetCacheServices arm64  <b5f37e2a434337019e4afe1a11d5dd4e> /System/Library/PrivateFrameworks/AssetCacheServices.framework/AssetCacheServices
0x19dfe6000 - 0x19e097fff NetworkServiceProxy arm64  <99e9d0bca947358c8727f047b2bd22ab> /System/Library/PrivateFrameworks/NetworkServiceProxy.framework/NetworkServiceProxy
0x19e098000 - 0x19e16cfff MMCS arm64  <e332a56b234c3efcacd23a564bb98fa5> /System/Library/PrivateFrameworks/MMCS.framework/MMCS
0x19e17a000 - 0x19e1e9fff CoreDAV arm64  <37a682dcba3a302290377b34499c62ec> /System/Library/PrivateFrameworks/CoreDAV.framework/CoreDAV
0x19e1ea000 - 0x19e21efff iCalendar arm64  <389964ac4a6831ecbbb3cdf7c148cd4d> /System/Library/PrivateFrameworks/iCalendar.framework/iCalendar
0x19e21f000 - 0x19e22bfff PersonaKit arm64  <0a918feb46063d6db95aa23b6f4ee8ce> /System/Library/PrivateFrameworks/PersonaKit.framework/PersonaKit
0x19e22c000 - 0x19e282fff CalendarFoundation arm64  <61af93fa1a793c72967d45fe5071d480> /System/Library/PrivateFrameworks/CalendarFoundation.framework/CalendarFoundation
0x19e283000 - 0x19e2b1fff PhotosFormats arm64  <ab80241bbd723a9daf4b2a7cdb5a219e> /System/Library/PrivateFrameworks/PhotosFormats.framework/PhotosFormats
0x19e2b2000 - 0x19e34bfff CalendarDatabase arm64  <4a4945aabdd733dabdd176dd06bd2c2d> /System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase
0x19e34c000 - 0x19e3a4fff CalendarDaemon arm64  <44660bd0d93237f3af93bdcff23fa68b> /System/Library/PrivateFrameworks/CalendarDaemon.framework/CalendarDaemon
0x19e3a5000 - 0x19e501fff CloudPhotoLibrary arm64  <461c44d6853d3c1b8577deea116e19bf> /System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/CloudPhotoLibrary
0x19e502000 - 0x19e5e6fff EventKit arm64  <63d7ac06e16b3407a0254df9ffa98595> /System/Library/Frameworks/EventKit.framework/EventKit
0x19e5e7000 - 0x19e619fff AssetsLibraryServices arm64  <e850778fef673c53b4471e87dd9b83e3> /System/Library/PrivateFrameworks/AssetsLibraryServices.framework/AssetsLibraryServices
0x19e64f000 - 0x19e677fff DCIMServices arm64  <940600c384993c83a3d619f48b2677f7> /System/Library/PrivateFrameworks/DCIMServices.framework/DCIMServices
0x19e678000 - 0x19e796fff CoreMediaStream arm64  <84c08bb10e9335618d4d5d4ce3a8611e> /System/Library/PrivateFrameworks/CoreMediaStream.framework/CoreMediaStream
0x19e797000 - 0x19e79efff XPCKit arm64  <483c8c95a9513bfea92a38ec26c34736> /System/Library/PrivateFrameworks/XPCKit.framework/XPCKit
0x19e87f000 - 0x19e898fff CloudPhotoServices arm64  <795ba783578f3e8e9a3c44316f71747e> /System/Library/PrivateFrameworks/CloudPhotoServices.framework/CloudPhotoServices
0x19e899000 - 0x19e8a4fff CoreRecents arm64  <2fef8a16fc623e269bccd1c21c950fcd> /System/Library/PrivateFrameworks/CoreRecents.framework/CoreRecents
0x19e8a5000 - 0x19e8c1fff MediaStream arm64  <1ba838bf66d93dbd814261e7ccdae31d> /System/Library/PrivateFrameworks/MediaStream.framework/MediaStream
0x19e8c2000 - 0x19edc3fff PhotoLibraryServices arm64  <3504c40d1ef830c486025f5fbb1d0da9> /System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PhotoLibraryServices
0x19edc4000 - 0x19eddffff PrototypeTools arm64  <24d7ea4dc99d33fd9e1462ed5d92a087> /System/Library/PrivateFrameworks/PrototypeTools.framework/PrototypeTools
0x19ede0000 - 0x19ee5ffff CoreSymbolication arm64  <c697350dd7103aa7b220567cf326693a> /System/Library/PrivateFrameworks/CoreSymbolication.framework/CoreSymbolication
0x19ee60000 - 0x19efaefff SearchFoundation arm64  <24b70e740ad03aafac4fe0b9a06bc41c> /System/Library/PrivateFrameworks/SearchFoundation.framework/SearchFoundation
0x19efaf000 - 0x19efb4fff IncomingCallFilter arm64  <5477f9113642385589837214ffc099a3> /System/Library/PrivateFrameworks/IncomingCallFilter.framework/IncomingCallFilter
0x19efb5000 - 0x19f06bfff iTunesStore arm64  <4b27b6d0cdff35c08c2993657b4e5519> /System/Library/PrivateFrameworks/iTunesStore.framework/iTunesStore
0x19f1c2000 - 0x19f1cafff CoreTime arm64  <b20bee3821923825b641230adc42b386> /System/Library/PrivateFrameworks/CoreTime.framework/CoreTime
0x19f1cb000 - 0x19f21bfff CoreAppleCVA arm64  <d3b298ffc45c3055b29a35260b8ecbae> /System/Library/PrivateFrameworks/CoreAppleCVA.framework/CoreAppleCVA
0x19f21c000 - 0x19f25afff DifferentialPrivacy arm64  <4e51f7b5592233ad8d1e499da9827c2c> /System/Library/PrivateFrameworks/DifferentialPrivacy.framework/DifferentialPrivacy
0x19f25b000 - 0x19f3fdfff AppleCVA arm64  <7601b3753d753bad8496859cf4b62993> /System/Library/PrivateFrameworks/AppleCVA.framework/AppleCVA
0x19f3fe000 - 0x19f4b5fff Montreal arm64  <7f1824260c6c31a3a7b9494f85164374> /System/Library/PrivateFrameworks/Montreal.framework/Montreal
0x19f4b6000 - 0x19f7d7fff Espresso arm64  <630c94e4727632c0a15a72d9084b309e> /System/Library/PrivateFrameworks/Espresso.framework/Espresso
0x19f7d8000 - 0x19f7defff MobileSystemServices arm64  <ae827d4ca2bf3cd0865dc1be70b0ff9e> /System/Library/PrivateFrameworks/MobileSystemServices.framework/MobileSystemServices
0x19f7df000 - 0x19f9cbfff Photos arm64  <edad6278ad5b30439e5c9aecf6da0e29> /System/Library/Frameworks/Photos.framework/Photos
0x19f9cc000 - 0x19fbeffff CoreML arm64  <ddbee838a9243aa2b3061908a9e5e41d> /System/Library/Frameworks/CoreML.framework/CoreML
0x19fbf0000 - 0x19fbf4fff CoreOptimization arm64  <a60da5d56a77385bab5ecf2a91e2cb78> /System/Library/PrivateFrameworks/CoreOptimization.framework/CoreOptimization
0x19fbf5000 - 0x19fc51fff SafariCore arm64  <883775cf59ff3e08a99a74e74b26a719> /System/Library/PrivateFrameworks/SafariCore.framework/SafariCore
0x19fc52000 - 0x19fca6fff CorePrediction arm64  <1bcb7bc51f703f46992bca964be95c1d> /System/Library/PrivateFrameworks/CorePrediction.framework/CorePrediction
0x19fcb3000 - 0x19fdaffff Navigation arm64  <b0b1391bcb733e74a7ca16bc6344d907> /System/Library/PrivateFrameworks/Navigation.framework/Navigation
0x19fdb0000 - 0x19fdc7fff ContactsDonation arm64  <bf74ea5613f0366da5e81a2be3e21c38> /System/Library/PrivateFrameworks/ContactsDonation.framework/ContactsDonation
0x19fdc8000 - 0x19fdf4fff Futhark arm64  <0689afcbd554372cbe1af54f31af5d37> /System/Library/PrivateFrameworks/Futhark.framework/Futhark
0x19fdf5000 - 0x19fe64fff NanoRegistry arm64  <4dd407a79baa3114b90e2730f11abbb3> /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry
0x19febd000 - 0x19fed3fff BaseBoardUI arm64  <98ca81e7be0632d0b25c175d75edc348> /System/Library/PrivateFrameworks/BaseBoardUI.framework/BaseBoardUI
0x19fed4000 - 0x19ff2bfff ContactsUICore arm64  <2be8b88c8dcd3ba1b38a483d50b14e2b> /System/Library/PrivateFrameworks/ContactsUICore.framework/ContactsUICore
0x19ff2c000 - 0x1a009efff ContactsUI arm64  <a2c4e97ff1653e3299a539ffcc96022e> /System/Library/Frameworks/ContactsUI.framework/ContactsUI
0x1a009f000 - 0x1a0169fff CorePDF arm64  <a775f7c706643da78354acc60a284057> /System/Library/PrivateFrameworks/CorePDF.framework/CorePDF
0x1a016a000 - 0x1a03fbfff Vision arm64  <38b4a5173b57371bbdfb7f3fdcd6509a> /System/Library/Frameworks/Vision.framework/Vision
0x1a03fc000 - 0x1a0910fff WebKit arm64  <2cb812df0acf393d9322bfaf629d44a6> /System/Library/Frameworks/WebKit.framework/WebKit
0x1a09a7000 - 0x1a09acfff ConstantClasses arm64  <605c3299145a3b2f9c36cb6c7058f488> /System/Library/PrivateFrameworks/ConstantClasses.framework/ConstantClasses
0x1a09ad000 - 0x1a09b5fff CertUI arm64  <a5088525bca939829b9339e5e263208c> /System/Library/PrivateFrameworks/CertUI.framework/CertUI
0x1a09b6000 - 0x1a0a00fff AXRuntime arm64  <f5eaad54e34c38f495d4519fed4aba0f> /System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime
0x1a0aab000 - 0x1a0b3afff MediaPlatform arm64  <81662649f4633308b5b52b750395dee7> /System/Library/PrivateFrameworks/MediaPlatform.framework/MediaPlatform
0x1a0b3b000 - 0x1a0b9bfff WebBookmarks arm64  <1a7161b7c02f344f991ba61679d93594> /System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks
0x1a0b9c000 - 0x1a0ba6fff DAAPKit arm64  <0f71d48594643d3391fb75c5215f7ff7> /System/Library/PrivateFrameworks/DAAPKit.framework/DAAPKit
0x1a0c9d000 - 0x1a0f70fff MediaLibraryCore arm64  <654e86b035673998a045160ad7f878ad> /System/Library/PrivateFrameworks/MediaLibraryCore.framework/MediaLibraryCore
0x1a0f73000 - 0x1a11ebfff MusicLibrary arm64  <f69096ed544f342eb913d9b6bb79b05d> /System/Library/PrivateFrameworks/MusicLibrary.framework/MusicLibrary
0x1a11ec000 - 0x1a1805fff VectorKit arm64  <ecd5e979112d3028ae578e6678cafa5f> /System/Library/PrivateFrameworks/VectorKit.framework/VectorKit
0x1a1806000 - 0x1a1a52fff MapKit arm64  <112d5fd16278301e9196e1364c481868> /System/Library/Frameworks/MapKit.framework/MapKit
0x1a1a53000 - 0x1a1c1cfff iTunesCloud arm64  <2a36043e136034fbb5b22c0da76aee45> /System/Library/PrivateFrameworks/iTunesCloud.framework/iTunesCloud
0x1a1c1d000 - 0x1a1cb6fff HomeSharing arm64  <d36a7b8691d43b8cb8d34e70b07bbd24> /System/Library/PrivateFrameworks/HomeSharing.framework/HomeSharing
0x1a1e30000 - 0x1a1e3efff NanoPreferencesSync arm64  <539e0687a5d434f98e4a78f61b382e14> /System/Library/PrivateFrameworks/NanoPreferencesSync.framework/NanoPreferencesSync
0x1a1e3f000 - 0x1a2274fff MediaPlayer arm64  <5f0112ecc0223555aa4596ee197c42ce> /System/Library/Frameworks/MediaPlayer.framework/MediaPlayer
0x1a2275000 - 0x1a2299fff MobileInstallation arm64  <a448765d3bf73d8b97d04149bb848d13> /System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation
0x1a229a000 - 0x1a22a1fff EmailAddressing arm64  <fead38e1ab5f388b8887625a45466aa1> /System/Library/PrivateFrameworks/EmailAddressing.framework/EmailAddressing
0x1a22a2000 - 0x1a22a4fff MessageSupport arm64  <4258e3ad611133d2acaf61c92e8b84a4> /System/Library/PrivateFrameworks/MessageSupport.framework/MessageSupport
0x1a22a5000 - 0x1a22a7fff InternationalTextSearch arm64  <39099b3f987d31f687e796ef6408fe2e> /System/Library/PrivateFrameworks/InternationalTextSearch.framework/InternationalTextSearch
0x1a22a8000 - 0x1a2301fff MIME arm64  <85fb617b486833d39a196040d5c6db10> /System/Library/PrivateFrameworks/MIME.framework/MIME
0x1a2302000 - 0x1a2337fff ProactiveSupport arm64  <927dd279b35532e0a2691c80935f0ac1> /System/Library/PrivateFrameworks/ProactiveSupport.framework/ProactiveSupport
0x1a2338000 - 0x1a236ffff Notes arm64  <1ef34c9995c83923ba3e9c2acf493bbb> /System/Library/PrivateFrameworks/Notes.framework/Notes
0x1a2370000 - 0x1a2436fff TelephonyUtilities arm64  <ea58f4466f7f34f69a651e1cfa3a58ed> /System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities
0x1a2437000 - 0x1a2472fff CalendarUIKit arm64  <6f214fa793eb3583a91679e8a99122e3> /System/Library/PrivateFrameworks/CalendarUIKit.framework/CalendarUIKit
0x1a2491000 - 0x1a24e6fff DataAccess arm64  <7a1236df8727353cac95d6bebd12bf6b> /System/Library/PrivateFrameworks/DataAccess.framework/DataAccess
0x1a24e7000 - 0x1a24f8fff AssetsLibrary arm64  <2ee46bc96d613916844c295709ac9905> /System/Library/Frameworks/AssetsLibrary.framework/AssetsLibrary
0x1a24f9000 - 0x1a26d2fff EventKitUI arm64  <1926f20b42f530fe90bf549cae4efe30> /System/Library/Frameworks/EventKitUI.framework/EventKitUI
0x1a27a7000 - 0x1a27befff CloudServices arm64  <0c2e61041acd354b877ad396b95bd36d> /System/Library/PrivateFrameworks/CloudServices.framework/CloudServices
0x1a27c4000 - 0x1a285dfff Social arm64  <ac10a1caa12032bfb977264cb6e93183> /System/Library/Frameworks/Social.framework/Social
0x1a285e000 - 0x1a2870fff KeychainCircle arm64  <6826ef76c9a6334ca6b69a26ba33b155> /System/Library/PrivateFrameworks/KeychainCircle.framework/KeychainCircle
0x1a28d7000 - 0x1a28f3fff CoreCDP arm64  <d3d827f0514f3b78bee8af9a6878f9e7> /System/Library/PrivateFrameworks/CoreCDP.framework/CoreCDP
0x1a28f4000 - 0x1a290bfff CoreFollowUp arm64  <dc39b1ffa8803a2ab1d53020b429e48a> /System/Library/PrivateFrameworks/CoreFollowUp.framework/CoreFollowUp
0x1a290c000 - 0x1a297bfff CoreSuggestions arm64  <c9953755a8d135bd9f5f3d055ce58074> /System/Library/PrivateFrameworks/CoreSuggestions.framework/CoreSuggestions
0x1a297c000 - 0x1a298cfff MailServices arm64  <62386db4052730d4a8e141cec1ae24fb> /System/Library/PrivateFrameworks/MailServices.framework/MailServices
0x1a2a1a000 - 0x1a2a42fff MailSupport arm64  <3c30c4d80b7b3fa3baf651a6f57ef7cd> /System/Library/PrivateFrameworks/MailSupport.framework/MailSupport
0x1a2a43000 - 0x1a2b8efff Message arm64  <6e6953cf23fd3bf7b07b1313ced7736d> /System/Library/PrivateFrameworks/Message.framework/Message
0x1a2d8f000 - 0x1a2e41fff CoreParsec arm64  <e4365d29daa43a4494d5686fb116f4e2> /System/Library/PrivateFrameworks/CoreParsec.framework/CoreParsec
0x1a2e6f000 - 0x1a2e9ffff SharedUtils arm64  <43ad539c0bce318db763e5e2cbb84a46> /System/Library/Frameworks/LocalAuthentication.framework/Support/SharedUtils.framework/SharedUtils
0x1a2ea0000 - 0x1a2edefff ContactsAutocomplete arm64  <1601bff8a43f37508b74038a7717f3a4> /System/Library/PrivateFrameworks/ContactsAutocomplete.framework/ContactsAutocomplete
0x1a30bc000 - 0x1a30bffff FTClientServices arm64  <aa69aff16411370085d61661ca0a6103> /System/Library/PrivateFrameworks/FTClientServices.framework/FTClientServices
0x1a30c4000 - 0x1a30c4fff MobileObliteration arm64  <3983c2b425ba3566a27201c750d31193> /System/Library/PrivateFrameworks/MobileObliteration.framework/MobileObliteration
0x1a32b2000 - 0x1a32c6fff LocalAuthentication arm64  <b1411cf833b83641a7252523193bca28> /System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication
0x1a32ca000 - 0x1a336dfff SpringBoardFoundation arm64  <8a33b4f8f7963f52bd7d4f3fe28a4450> /System/Library/PrivateFrameworks/SpringBoardFoundation.framework/SpringBoardFoundation
0x1a35ba000 - 0x1a35c8fff SetupAssistantSupport arm64  <15c081c7d48b3afebf60eb9b712519a9> /System/Library/PrivateFrameworks/SetupAssistantSupport.framework/SetupAssistantSupport
0x1a35c9000 - 0x1a35fcfff SetupAssistant arm64  <129444f03e1b353f9795e6bf83341591> /System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant
0x1a3638000 - 0x1a3644fff DistributedEvaluation arm64  <45941b42b89a3afcb4ac8b33144ccf2b> /System/Library/PrivateFrameworks/DistributedEvaluation.framework/DistributedEvaluation
0x1a3645000 - 0x1a3648fff HSAAuthentication arm64  <936473dc30633d81bda6087c0fe6cb75> /System/Library/PrivateFrameworks/HSAAuthentication.framework/HSAAuthentication
0x1a3649000 - 0x1a3652fff MobileStorage arm64  <148c72bf22433e58a1e4fb32a489c7f5> /System/Library/PrivateFrameworks/MobileStorage.framework/MobileStorage
0x1a3692000 - 0x1a36eefff ImageCapture arm64  <ccba7b9494033932b5b5558ba6bc5b1e> /System/Library/PrivateFrameworks/ImageCapture.framework/ImageCapture
0x1a38cf000 - 0x1a38eefff LatentSemanticMapping arm64  <5206b9743daa36f39d914706b25f37e7> /System/Library/PrivateFrameworks/LatentSemanticMapping.framework/LatentSemanticMapping
0x1a38ef000 - 0x1a3d04fff PassKitCore arm64  <53cd52273942333a88c440bca04d60cc> /System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore
0x1a42a2000 - 0x1a42dafff TelephonyUI arm64  <6889423dd37933489dc21256d014e1bc> /System/Library/PrivateFrameworks/TelephonyUI.framework/TelephonyUI
0x1a42db000 - 0x1a42f2fff CoreSDB arm64  <d2b58f8dbb1f36a18a0f17c043ba8c92> /System/Library/PrivateFrameworks/CoreSDB.framework/CoreSDB
0x1a42f3000 - 0x1a4381fff IMSharedUtilities arm64  <17838d57ecee3b7181a967de4d77cc38> /System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities
0x1a4382000 - 0x1a4387fff LinguisticData arm64  <ea730959fc8f382b9d6da155b0e44a67> /System/Library/PrivateFrameworks/LinguisticData.framework/LinguisticData
0x1a48ff000 - 0x1a49fffff ResponseKit arm64  <2649703054563f06bd9e0025a7f94ed8> /System/Library/PrivateFrameworks/ResponseKit.framework/ResponseKit
0x1a4acf000 - 0x1a4ae6fff EmojiFoundation arm64  <5a6393b36aa83661bdd8183fab7892e8> /System/Library/PrivateFrameworks/EmojiFoundation.framework/EmojiFoundation
0x1a4ae7000 - 0x1a4bfcfff IMDPersistence arm64  <06d6cabf64e13bfb840ce810ba4496e0> /System/Library/PrivateFrameworks/IMDPersistence.framework/IMDPersistence
0x1a52b7000 - 0x1a52f4fff PersonalizationPortrait arm64  <c7c63469c06032e886f992a71c5046af> /System/Library/PrivateFrameworks/PersonalizationPortrait.framework/PersonalizationPortrait
0x1a5665000 - 0x1a572bfff PDFKit arm64  <1baa2b57d3ad37c3b6ba52e54fe1c42f> /System/Library/Frameworks/PDFKit.framework/PDFKit
0x1a5852000 - 0x1a5a00fff IMCore arm64  <117b40b7b2943fdf8ba30c4753d3429e> /System/Library/PrivateFrameworks/IMCore.framework/IMCore
0x1a5a1a000 - 0x1a5a59fff Pasteboard arm64  <8277df3a33183d4aaf9d7901642ff4fc> /System/Library/PrivateFrameworks/Pasteboard.framework/Pasteboard
0x1a5a5a000 - 0x1a5a6ffff FMCoreLite arm64  <46920aa704643a67bcf77cda32af2710> /System/Library/PrivateFrameworks/FMCoreLite.framework/FMCoreLite
0x1a5aa1000 - 0x1a5ab3fff MobileDeviceLink arm64  <a00b87e31ebe33b88e0cfe0d1b4548aa> /System/Library/PrivateFrameworks/MobileDeviceLink.framework/MobileDeviceLink
0x1a5b75000 - 0x1a5b8ffff MaterialKit arm64  <7c80641cce683d52979650ea8fbfe2a0> /System/Library/PrivateFrameworks/MaterialKit.framework/MaterialKit
0x1a5b90000 - 0x1a5be3fff MobileBackup arm64  <0461e0b5f8573d5da78290e6c21ef496> /System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup
0x1a5be4000 - 0x1a5c31fff SafariSafeBrowsing arm64  <466e66ac4dc43c42b7ab475181635f80> /System/Library/PrivateFrameworks/SafariSafeBrowsing.framework/SafariSafeBrowsing
0x1a69b1000 - 0x1a69d3fff DuetActivityScheduler arm64  <39c93025380138998a3845e97dc90edd> /System/Library/PrivateFrameworks/DuetActivityScheduler.framework/DuetActivityScheduler
0x1a6ab6000 - 0x1a6ab7fff LegacyHandle arm64  <0de1d9a748f4307cb2e5d67e6336cf76> /System/Library/PrivateFrameworks/AVConference.framework/Frameworks/LegacyHandle.framework/LegacyHandle
0x1a6c01000 - 0x1a6c01fff libAWDProtobufFacetimeiMessage.dylib arm64  <e84edc942cc030cd9b07eb05adb527ba> /usr/lib/libAWDProtobufFacetimeiMessage.dylib
0x1a6c20000 - 0x1a6c5afff ViceroyTrace arm64  <87e3fc77cf0c388cb143920e0da466ac> /System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/ViceroyTrace
0x1a6c5b000 - 0x1a6c66fff AppConduit arm64  <463f0db712053d029e0482b868b7250d> /System/Library/PrivateFrameworks/AppConduit.framework/AppConduit
0x1a6f39000 - 0x1a71d1fff VideoProcessing arm64  <4c77a98d787f3263940ebbeb847f222a> /System/Library/PrivateFrameworks/VideoProcessing.framework/VideoProcessing
0x1a7243000 - 0x1a724efff SimpleKeyExchange arm64  <2d5a1ba289d03f7c81567374566ddcd9> /System/Library/PrivateFrameworks/AVConference.framework/Frameworks/SimpleKeyExchange.framework/SimpleKeyExchange
0x1a724f000 - 0x1a724ffff snatmap arm64  <852eb58d24b73bf68bc90236848e1238> /System/Library/PrivateFrameworks/AVConference.framework/Frameworks/snatmap.framework/snatmap
0x1a72b7000 - 0x1a72fafff ICE arm64  <3393d4312d79317c9e873bb34d4ce052> /System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ICE.framework/ICE
0x1a7614000 - 0x1a7669fff CallKit arm64  <1644f0247e4f39df9ff1198c5fddd574> /System/Library/Frameworks/CallKit.framework/CallKit
0x1a76cf000 - 0x1a7723fff IMAVCore arm64  <9570c66c71893f729dcd04106bd39063> /System/Library/PrivateFrameworks/IMAVCore.framework/IMAVCore
0x1a7ac1000 - 0x1a7acdfff WirelessCoexManager arm64  <4dcd6d0ac8063b82acd708ce855aa85b> /System/Library/PrivateFrameworks/WirelessCoexManager.framework/WirelessCoexManager
0x1a7dd1000 - 0x1a81ecfff AVConference arm64  <844904bb987f376cbe2de5f4af9dc097> /System/Library/PrivateFrameworks/AVConference.framework/AVConference
0x1a8399000 - 0x1a83eafff LoggingSupport arm64  <f972f6275bc7395c8c3f9e6a6d2b653b> /System/Library/PrivateFrameworks/LoggingSupport.framework/LoggingSupport
0x1a862f000 - 0x1a863efff Speech arm64  <7487789b11803fee95339460aa20972c> /System/Library/Frameworks/Speech.framework/Speech
0x1a9136000 - 0x1a913cfff VoicemailStore arm64  <b6c53a5fa434379a89f5d2cdebed6be0> /System/Library/PrivateFrameworks/VoicemailStore.framework/VoicemailStore
0x1aa3c3000 - 0x1aa3e6fff AppSupportUI arm64  <08fb2606183e3704b634e045131d7c24> /System/Library/PrivateFrameworks/AppSupportUI.framework/AppSupportUI
0x1aa3e7000 - 0x1aa435fff CallHistory arm64  <28095b58878839ef92aa880ae71bf572> /System/Library/PrivateFrameworks/CallHistory.framework/CallHistory
0x1aa9e1000 - 0x1aaa28fff VisualVoicemail arm64  <2db4191095b63eeab8f7841e34745cd4> /System/Library/PrivateFrameworks/VisualVoicemail.framework/VisualVoicemail
0x1ab076000 - 0x1ab07bfff kperf arm64  <7a89ef48a21d3f1e9665d58b1a3fe579> /System/Library/PrivateFrameworks/kperf.framework/kperf
0x1ab0f6000 - 0x1ab101fff IdentityLookup arm64  <99f20950cf1c3624868e201d961d9ec0> /System/Library/Frameworks/IdentityLookup.framework/IdentityLookup
0x1ab2cd000 - 0x1ab2edfff CellularPlanManager arm64  <bb45ce1201a733f18234c94b7a908794> /System/Library/PrivateFrameworks/CellularPlanManager.framework/CellularPlanManager
0x1ab355000 - 0x1ab383fff FMF arm64  <526fffdc994835a59eb6dbb9f1b25fca> /System/Library/PrivateFrameworks/FMF.framework/FMF
0x1ab4ac000 - 0x1ab4b4fff kperfdata arm64  <06520184071d31719b159cfb87130d35> /System/Library/PrivateFrameworks/kperfdata.framework/kperfdata
0x1ab4f7000 - 0x1ab4fefff libdscsym.dylib arm64  <ca91952eaf3733998d8f6b2920e8fac2> /usr/lib/libdscsym.dylib
0x1ab4ff000 - 0x1ab503fff libsysdiagnose.dylib arm64  <1b18aad51d713d6fac77e5f23e358eb2> /usr/lib/libsysdiagnose.dylib
0x1ab533000 - 0x1ab5dcfff AutoLoop arm64  <6768ea2418c73c70b490e8588edca6bb> /System/Library/PrivateFrameworks/AutoLoop.framework/AutoLoop
0x1ab69e000 - 0x1ab6c2fff ControlCenterUIKit arm64  <74adc78f87d33579a2c54c1da19fb982> /System/Library/PrivateFrameworks/ControlCenterUIKit.framework/ControlCenterUIKit
0x1ab74c000 - 0x1ab754fff IDSKVStore arm64  <3b9fe078f3953b5e9fc260ddab202243> /System/Library/PrivateFrameworks/IDSKVStore.framework/IDSKVStore
0x1ab8a1000 - 0x1ab8d8fff ktrace arm64  <62185159e42038b99ebfebf8c729e61b> /System/Library/PrivateFrameworks/ktrace.framework/ktrace
0x1acf15000 - 0x1acf18fff FoundInAppsPlugins arm64  <26785f62e50c3f5cb580c3302212538c> /System/Library/PrivateFrameworks/FoundInAppsPlugins.framework/FoundInAppsPlugins
0x1ad65d000 - 0x1ad6b9fff ProactiveML arm64  <eda3a39d66b03ac4bcef8070f63c1c78> /System/Library/PrivateFrameworks/ProactiveML.framework/ProactiveML
0x1adb7b000 - 0x1adb8afff CTCarrierSpace arm64  <62db6751c46f33e595a6322d761918fb> /System/Library/PrivateFrameworks/CTCarrierSpace.framework/CTCarrierSpace
0x1adfa2000 - 0x1adfe2fff DataDetectorsNaturalLanguage arm64  <20e9d50f1c5f337f95c8f1cc9a56ef33> /System/Library/PrivateFrameworks/DataDetectorsNaturalLanguage.framework/DataDetectorsNaturalLanguage
0x1adfe3000 - 0x1ae006fff DeviceIdentity arm64  <923d44a1fea0305ea23f0745e8344bff> /System/Library/PrivateFrameworks/DeviceIdentity.framework/DeviceIdentity
0x1aec72000 - 0x1aec79fff PPTopicExtractionPlugin arm64  <e29b68e438953cbd817b50df303adf69> /System/Library/PrivateFrameworks/PPTopicExtractionPlugin.framework/PPTopicExtractionPlugin
0x1aff79000 - 0x1afff1fff Rapport arm64  <24b8a966d17839a49b24b103c889e048> /System/Library/PrivateFrameworks/Rapport.framework/Rapport
0x1b002d000 - 0x1b006ffff SignpostSupport arm64  <8fd93797d31730aeb5e66fd10b320825> /System/Library/PrivateFrameworks/SignpostSupport.framework/SignpostSupport
0x1b0a6a000 - 0x1b0ac7fff UserActivity arm64  <7d8f588f5138337c84e7a7daf55bed41> /System/Library/PrivateFrameworks/UserActivity.framework/UserActivity
0x1b0f67000 - 0x1b0f6efff libMatch.1.dylib arm64  <0ab6e6fae4a039eaad03429b1c74d823> /usr/lib/libMatch.1.dylib
0x1b0fb7000 - 0x1b0fccfff libtailspin.dylib arm64  <97a536ebbd543e8bb5fd2c4442403d8e> /usr/lib/libtailspin.dylib
0x1b12c5000 - 0x1b158bfff RawCamera arm64  <7ff8546416f7397f85ceb362ac8b31e3> /System/Library/CoreServices/RawCamera.bundle/RawCamera
0x1b185e000 - 0x1b1872fff libCGInterfaces.dylib arm64  <7a9488d7f89931b484428689e920c6ba> /System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/Libraries/libCGInterfaces.dylib
0x1b3f01000 - 0x1b3f28fff CoreServicesInternal arm64  <76068e39b78c32f6abaab1117775a851> /System/Library/PrivateFrameworks/CoreServicesInternal.framework/CoreServicesInternal
0x1b4025000 - 0x1b4248fff CoreSuggestionsInternals arm64  <ae8b6201fd2c3e04bc1a86d550839538> /System/Library/PrivateFrameworks/CoreSuggestionsInternals.framework/CoreSuggestionsInternals
0x1b4575000 - 0x1b457ffff Email arm64  <f43586aba5f632b98aa3e394a730d993> /System/Library/PrivateFrameworks/Email.framework/Email
0x1b4580000 - 0x1b4587fff EmailCore arm64  <1612a2600d42332fb0588470a306da0d> /System/Library/PrivateFrameworks/EmailCore.framework/EmailCore
0x1b4595000 - 0x1b45a7fff libGSFontCache.dylib arm64  <654308310b4931a2bec34675aa3d8a45> /System/Library/PrivateFrameworks/FontServices.framework/libGSFontCache.dylib
0x1b45a8000 - 0x1b45d8fff libTrueTypeScaler.dylib arm64  <a39a0f8d03d63ca49d121d74ae992fde> /System/Library/PrivateFrameworks/FontServices.framework/libTrueTypeScaler.dylib
0x1b5fda000 - 0x1b5fdefff InternationalSupport arm64  <27cc782b373537af9aa24edffacf09e2> /System/Library/PrivateFrameworks/InternationalSupport.framework/InternationalSupport
0x1b7362000 - 0x1b736efff PersonaUI arm64  <b729eda30d223e5aa2de50984f474fe5> /System/Library/PrivateFrameworks/PersonaUI.framework/PersonaUI
0x1b7799000 - 0x1b77a3fff SignpostCollection arm64  <9f5402f71bf03953aebed55638322eaf> /System/Library/PrivateFrameworks/SignpostCollection.framework/SignpostCollection
0x1b7d60000 - 0x1b7d66fff TextInputUI arm64  <a603ed492ef03f318723c3f7b49eaaf4> /System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI
0x1b81e6000 - 0x1b81e9fff XCTTargetBootstrap arm64  <04c9799049f336cab2c33ed8c1370c7b> /System/Library/PrivateFrameworks/XCTTargetBootstrap.framework/XCTTargetBootstrap
0x1b8227000 - 0x1b823afff libEDR arm64  <71cf2c7e251c3fc78fcacd54e8be8e4a> /System/Library/PrivateFrameworks/libEDR.framework/libEDR
0x1b8bce000 - 0x1b8bdbfff libMobileGestaltExtensions.dylib arm64  <bc2bc349f34f3eaa82614238d10f889a> /usr/lib/libMobileGestaltExtensions.dylib
0x1b8ce9000 - 0x1b8ce9fff libcharset.1.dylib arm64  <407954967d42398ba8f25e1891f39960> /usr/lib/libcharset.1.dylib
0x1b9759000 - 0x1b975afff libsandbox.1.dylib arm64  <be173ca6237a37bc84342689de420109> /usr/lib/libsandbox.1.dylib
0x1b9915000 - 0x1b9a52fff CoreServices arm64  <5f53079ab0e836b7af624d05ba9fc41d> /System/Library/Frameworks/CoreServices.framework/CoreServices
0x1b9a74000 - 0x1b9a7bfff IdentityLookupUI arm64  <00b2477d180234c7b9b7f3a6e12b5a9d> /System/Library/Frameworks/IdentityLookupUI.framework/IdentityLookupUI
0x1b9a7c000 - 0x1b9a95fff MPSRayIntersector arm64  <d6d05474d6bd3365aaeb79616fd7ba20> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSRayIntersector.framework/MPSRayIntersector
0x1b9ac2000 - 0x1b9be8fff Network arm64  <4ad46f271d3e3acd98d5b109e2e8b04a> /System/Library/Frameworks/Network.framework/Network
0x1b9bf9000 - 0x1b9c07fff ANEServices arm64  <dcb20117f8ab33c0946f2c555017d257> /System/Library/PrivateFrameworks/ANEServices.framework/ANEServices
0x1b9c0c000 - 0x1b9c10fff ASEProcessing arm64  <9f902a0c35083c36bb8f44de375b06bb> /System/Library/PrivateFrameworks/ASEProcessing.framework/ASEProcessing
0x1b9c11000 - 0x1b9c1cfff AXCoreUtilities arm64  <c5673a50c6a43cbda01d7fba9fe4e454> /System/Library/PrivateFrameworks/AXCoreUtilities.framework/AXCoreUtilities
0x1b9e9c000 - 0x1b9fe9fff AppleMediaServices arm64  <c384d4aa6f5936d3ae65f48583fcd9b3> /System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices
0x1b9fea000 - 0x1b9ff9fff AppleNeuralEngine arm64  <49ccc308846e34d5850be88fda6000fb> /System/Library/PrivateFrameworks/AppleNeuralEngine.framework/AppleNeuralEngine
0x1ba172000 - 0x1ba1a7fff C2 arm64  <175ce2e91e4f38798a9c43e0437b0bf0> /System/Library/PrivateFrameworks/C2.framework/C2
0x1ba675000 - 0x1ba681fff CoreIDV arm64  <8cd4465f19c333aa83bb2fc590e29388> /System/Library/PrivateFrameworks/CoreIDV.framework/CoreIDV
0x1ba7bf000 - 0x1ba812fff DocumentManager arm64  <8e270887737430b099a4d43900e2ee65> /System/Library/PrivateFrameworks/DocumentManager.framework/DocumentManager
0x1ba85d000 - 0x1ba865fff HearingCore arm64  <a9f47266ebbc3b778d22874201c914fa> /System/Library/PrivateFrameworks/HearingCore.framework/HearingCore
0x1ba951000 - 0x1ba955fff IdleTimerServices arm64  <ae57544db59f355db6b4aa15625512a5> /System/Library/PrivateFrameworks/IdleTimerServices.framework/IdleTimerServices
0x1baa37000 - 0x1baa5ffff MetadataUtilities arm64  <da900e8bb5123acd9d077abf78c2b12e> /System/Library/PrivateFrameworks/MetadataUtilities.framework/MetadataUtilities
0x1bbbcc000 - 0x1bbc18fff OTSVG arm64  <793493c68ab13330a421f7cbd5c61f52> /System/Library/PrivateFrameworks/OTSVG.framework/OTSVG
0x1bbc61000 - 0x1bbd0bfff PersonalizationPortraitInternals arm64  <0e9fa50d1fdf32578e08f0799b19e113> /System/Library/PrivateFrameworks/PersonalizationPortraitInternals.framework/PersonalizationPortraitInternals
0x1bbd0c000 - 0x1bbd66fff PhotoFoundation arm64  <5f5043339fd935359daf0537dcfa0fd5> /System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation
0x1bbdb6000 - 0x1bbdf7fff PhotosImagingFoundation arm64  <47a9fcbbfd79312995412bee560bb889> /System/Library/PrivateFrameworks/PhotosImagingFoundation.framework/PhotosImagingFoundation
0x1bbe59000 - 0x1bbea6fff ROCKit arm64  <91466a6e18843da08642493d2423261f> /System/Library/PrivateFrameworks/ROCKit.framework/ROCKit
0x1bbea7000 - 0x1bbec0fff RTTUI arm64  <cdd5c76096af3fee8f2804ad5e05576c> /System/Library/PrivateFrameworks/RTTUI.framework/RTTUI
0x1bbec1000 - 0x1bbef4fff RTTUtilities arm64  <a7b2affbe1b132558bc139734a6c17fe> /System/Library/PrivateFrameworks/RTTUtilities.framework/RTTUtilities
0x1bc0c0000 - 0x1bc0d1fff RemoteTextInput arm64  <0be791545f9234fabb2226890e12fe02> /System/Library/PrivateFrameworks/RemoteTextInput.framework/RemoteTextInput
0x1bc0f9000 - 0x1bc18dfff SampleAnalysis arm64  <c619b57ac4853071b9ff81db337b16fc> /System/Library/PrivateFrameworks/SampleAnalysis.framework/SampleAnalysis
0x1bc273000 - 0x1bc275fff ShortcutUIKit arm64  <d56aa0902f053c1a905cf75e59403abb> /System/Library/PrivateFrameworks/ShortcutUIKit.framework/ShortcutUIKit
0x1bc2e2000 - 0x1bc2f6fff SiriInstrumentation arm64  <68f57b9c927235aba58111816e6c1c9a> /System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation
0x1bc338000 - 0x1bc33ffff StatsKit arm64  <464a62c99cbd340d9d96c9bed41ed318> /System/Library/PrivateFrameworks/StatsKit.framework/StatsKit
0x1bcf5f000 - 0x1be043fff UIKitCore arm64  <a1f463bfcf9b3796ba9e7c2b40617fae> /System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore
0x1be044000 - 0x1be04efff UIKitServices arm64  <ad0c5c64bbb83b17b4ac0706c9b9487b> /System/Library/PrivateFrameworks/UIKitServices.framework/UIKitServices
0x1be04f000 - 0x1be055fff URLFormatting arm64  <c842e0066f893fc2bcd763b29e02b7dc> /System/Library/PrivateFrameworks/URLFormatting.framework/URLFormatting

EOF
