# Screen-Based Augmented Reality Surgical Guidance Application

Final project for the Medical Augmented Reality course @TUM

## Objective:
Create a screen-based AR application using Unity and Vuforia (or any preferred AR library) to
overlay anatomical CT data on an image target and simulate surgical instrument tracking for a
guided procedure.

## Tasks
**1. Overlay CT Data on an Image Target**
   * Use the provided CT scan data
   * Overlay the scan data (or a mesh extracted from it) onto a marker using Vuforia or a similar tracking library.
   * Use tools like **3D Slicer** to extract meshes from the CT scan and refine them with **Blender** or **MeshLab** if necessary

**2. Track a SUrgical Instrument**
  * Use an additional marker to track a simulated surgical instrument (e.g., a pen).
  * Import a 3D model of a surgical instrument from free sources such as:
  * Align the virtual instrument with the physical object in Unity: Calibrate the instrument tip using **tool-tip pivot calibration** (MaLibU) (Fallback: If the calibration does not work, you can manually approximate it by “eyeballing”).

**3. Define Target Points:**
  *  Choose 3 target points inside the anatomy, and mark them e.g. by spheres
  * Create visual navigation aids to guide the user to these points. Examples include:
    * Color-coded lines or 3D arrows.
    * Dynamic color changes of the instrument or target.
    * 2D/3D widgets indicating distance and direction.

**4. Indicate Targeting Success:**
  * Detect when the surgical tool reaches a target point (e.g., distance <1 cm).
  * Provide clear success feedback: visual cues (e.g., change in target color, animation) or audio feedback (e.g., a beep or congratulatory message).
  * Guide the user to the next target until all points are reached.

### Device Requirement:
Application should run on your phone, tablet, or PC.

## Deliverables

  **1. Video Demonstration (2 minutes):** Showcase the application functionality.
  
  **2. Short Description (Half-Page):** Explain the implemented features.
  
  **3. Code submission** (zip file or publicly accessible Git repository)

