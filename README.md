# FPS independent melee tracing system in Unreal Engine-C++ 

Built an FPS-independent melee tracing system in Unreal Engine (C++) to keep hit detection reliable on both low-end and high-end Devices.

On slower machines where frame drops can cause missed hits, the weapon’s motion is adaptively reconstructed into collision volumes so coverage remains consistent. On higher frame rates, the system naturally reduces work while maintaining accuracy. 
This keeps gameplay fair and deterministic regardless of performance differences.
A solid reminder that good gameplay systems shouldn’t rely on frame rate assumptions.

https://github.com/user-attachments/assets/113ec5ef-040c-46a2-98e5-4a06d121e3cb

