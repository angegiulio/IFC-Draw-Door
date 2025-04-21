# IFC-Draw-Door

IFC Door Visualizer in Google Colab

This script uses IfcOpenShell and Plotly to extract and visualize a solid 3D diagram of a door from an IFC model, directly in Google Colab. It overlays a wireframe to highlight edges, producing a clear, technical-style render.


---

**Features**

Load and parse IFC files in Colab

Extract 3D geometry of the first IfcDoor

Render a solid mesh with wireframe overlay

Set a fixed front-view camera

Clean scene: no axes, gridlines, or labels

Export high-resolution PNG snapshots



---

**Requirements**

Google Colab

Python 3.7+

Python packages:

ifcopenshell

plotly

kaleido (for exporting images)



**Install with:**
!pip install ifcopenshell plotly kaleido


---

**How to Use**

1. Upload your IFC file (e.g. model.ifc) to the Colab environment.


2. Run each cell in order:

Load the IFC

Extract geometry of the first door

Render the diagram



3. View the interactive 3D diagram.


4. Export a front-view image (optional).
