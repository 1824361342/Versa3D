# Versa3D

An intelligent 3D printer slicing software that improves process and machine paramters over builds, and works will all additive manufacturing methods, not only FDM, but SLA/DLP, SLS/SLM, BJ, etc. An included scripting engine will make it easy for custom machines to use the software, as well as allowing for a modular 3D printing platorm. 

Thank you to [Matt Keeter (mkeeter)](https://github.com/mkeeter) for providing an [excellent starting codebase](https://github.com/mkeeter/fstl) to allow me to easily begin on this application, without having to re-implement STL data loading.

### Current UI

<p align="center">
  <img src="https://github.com/alitoyserkani/Versa3D/blob/master/info/interfaceScreenShot.png" />
</p>

### Development Updates

- Custom slicing and toolpath algorithms based on machine parameters using ML concepts is currently in development inside another private repository. Slic3r is used for now to continue building the desktop application interface.

- Design implementations for the scripting engine are currently being developed
- Graphics will be updated to allow for a more interactive and realistic experience

### Current To Do List
- Finish ML model and integrate with application for machine file creation
- Create importable printer CAD models to be displayed in background of OpenGL widget 
- Finish scripting engine functionality and integrate with main application
- Change software architechture to allow for printer scalability and networking integratiom.
- Add more user information in UI, such as part dimensions, layer dimensions, and all machine paramters

### Dependencies

The only current dependecy for this application is Qt, however, plugin libraries such as OpenCV will be optional for increased intelligence.

### Application History

Development Started: August 14th, 2017

