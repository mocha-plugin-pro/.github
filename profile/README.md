# Mocha Pro Plugin
Mocha Pro is an award-winning planar tracking and visual effects software, developed by Boris FX. It's renowned in the film, broadcast, and post-production industries for its powerful capabilities, especially in handling complex motion tracking, rotoscoping, object removal, and stabilization tasks.

While it can be used as a standalone application, it's incredibly popular as a plugin for major host applications like Adobe After Effects, Adobe Premiere Pro, Avid Media Composer, Foundry Nuke, Blackmagic Design Fusion, DaVinci Resolve, and more (via OFX support). This plugin integration allows for a seamless workflow, often using the host's media engine and project format.


The core technology that makes Mocha Pro so powerful is its planar tracking algorithm. Unlike traditional point trackers that follow individual pixels, planar tracking analyzes patterns of pixels on a flat (or semi-flat, deforming) surface. This makes it incredibly robust for tracking elements even when they go off-screen, are partially obscured, or are out of focus.
## Key Features and Uses of Mocha Pro Plugin:
1. Planar Motion Tracking:

- Foundation of everything: This is the heart of Mocha Pro. It accurately tracks the motion, scale, rotation, shear, and perspective of planes within your footage.

- Difficult Shots: Excels at tracking challenging shots with motion blur, grain, or even objects moving in front of the area you need to track.

- PowerMesh Tracking: An advanced planar tracking method that allows you to track organic, deforming surfaces (like skin, fabric, muscles) by defining a mesh that warps with the underlying surface.

2. Rotoscoping and Masking:

- X-Splines and Bezier Splines: Tools for drawing precise masks around objects.

- Magnetic Edge Snapping: Helps automatically snap spline points to the edges of objects, greatly speeding up the masking process.

- Roto with Motion Blur: Generate realistic motion blur on your roto shapes based on the tracked motion.

- AI-powered Roto & Masking: Newer versions include tools like Object Brush and Matte Assist that use AI to semi-automate the creation of animated mattes, saving significant time.

- Face Detection: Automatically detect, track, and manage multiple faces for privacy masking, selective blurring, or color correction.

3. Object Removal (Wire Removal, Rig Removal, Clean Plating):

- Content-Aware Fill on Steroids: Leveraging its planar tracking, Mocha Pro can "paint out" unwanted objects, wires, or even entire people from moving footage. It does this by analyzing clean frames and blending pixels seamlessly.

- Static Scene Remove: For locked-off or static shots, it can remove objects without needing tracking.

- Mega Plates: Creates an extended, stitched frame for easier object removal, clean plating, and set extensions on a larger "canvas."

4. Image Stabilization:

- Camera Stabilization: Smooth out shaky camera footage while maintaining original camera motion.

- Object Stabilization: Stabilize a specific object within a moving shot.

- Inverse-Warped Flattened Surface: With PowerMesh, it can create a flattened, stabilized surface, perfect for paint fixes that can then be propagated back to the original moving footage.

5. Screen Inserts and Replacements:

- Easily replace screens on phones, monitors, or signs within moving footage, automatically matching perspective, motion blur, and distortion.

- Insert Module: Streamlines the process of placing new content onto tracked surfaces.

6. Lens Calibration Tools:

- Lens Module: Helps analyze and remove unwanted lens distortion (e.g., barrel or pincushion distortion) or match distortion for realistic composites.

7. 3D Camera Solver:

- Unlike feature-based 3D trackers, Mocha's 3D Camera Solver works by solving the 3D camera motion based on user-selected planar data. This can be faster and more reliable for certain types of shots, especially those with low detail or foreground occlusions.

- Integration with SynthEyes: Newer versions integrate core 3D tracking algorithms from SynthEyes for enhanced camera solves.

- Exports 3D camera data to various formats (FBX, USD, Alembic) for use in other 3D applications.

8. Stereoscopic 3D & 360/VR Support:

- Offers specialized planar tracking, masking, and object removal workflows for stereo 3D and 360/VR footage, helping to reduce manual keyframing in these complex environments.

9. Integration and Export:

- Seamless Host Integration: As a plugin, it integrates deeply with host applications, allowing direct launching and data transfer without complex file management.

- Flexible Exports: Exports tracking data, roto shapes, and 3D data in numerous formats compatible with various VFX software.

- GPU Acceleration: Utilizes GPU for faster processing and rendering, especially for tasks like object removal.

Mocha Pro is an essential tool for VFX artists and editors who need precise and robust tracking and masking capabilities to achieve professional-level visual effects.
