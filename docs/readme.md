Test of new documentation (09.2025)
```mermaid
classDiagram
  class mesoSPIM {
  }
  class mesoSPIM_Control {
  }
  class src {
  }
  class WebcamWindow {
  }
  class devices {
  }
  class cameras {
  }
  class Demo_Camera {
  }
  class hamamatsu {
  }
  class hamamatsu_camera {
  }
  class filter_wheels {
  }
  class ZWO_EFW {
  }
  class pyzwoefw {
  }
  class mesoSPIM_FilterWheel {
  }
  class joysticks {
  }
  class Demo_SidePanel {
  }
  class logitech {
  }
  class mesoSPIM_JoystickHandlers {
  }
  class lasers {
  }
  class Demo_LaserEnabler {
  }
  class mesoSPIM_LaserEnabler {
  }
  class servos {
  }
  class shutters {
  }
  class Demo_Shutter {
  }
  class NI_Shutter {
  }
  class stages {
  }
  class asi {
  }
  class asicontrol {
  }
  class galil {
  }
  class galilcontrol {
  }
  class gclib {
  }
  class mesoSPIM_AcquisitionManagerWindow {
  }
  class mesoSPIM_Camera {
  }
  class mesoSPIM_CameraWindow {
  }
  class mesoSPIM_ContrastWindow {
  }
  class mesoSPIM_Core {
  }
  class mesoSPIM_ImageWriter {
  }
  class mesoSPIM_MainWindow {
  }
  class mesoSPIM_Optimizer {
  }
  class mesoSPIM_ScriptWindow {
  }
  class mesoSPIM_Serial {
  }
  class mesoSPIM_Stages {
  }
  class mesoSPIM_State {
  }
  class mesoSPIM_TileViewWindow {
  }
  class mesoSPIM_WaveFormGenerator {
  }
  class mesoSPIM_Zoom {
  }
  class utils {
  }
  class acquisitions {
  }
  class delegates {
  }
  class filename_wizard {
  }
  class focus_tracking_wizard {
  }
  class image_processing_wizard {
  }
  class models {
  }
  class multicolor_acquisition_builder {
  }
  class multicolor_acquisition_wizard {
  }
  class optimization {
  }
  class utility_functions {
  }
  class waveforms {
  }
  class widgets {
  }
  class test {
  }
  class test_serial {
  }
  class test_tiling {
  }
  class test_writing_speed {
  }
  mesoSPIM_Control --> mesoSPIM_MainWindow
  mesoSPIM_FilterWheel --> ZWO_EFW
  mesoSPIM_FilterWheel --> pyzwoefw
  mesoSPIM_JoystickHandlers --> Demo_SidePanel
  mesoSPIM_JoystickHandlers --> logitech
  mesoSPIM_AcquisitionManagerWindow --> delegates
  mesoSPIM_AcquisitionManagerWindow --> filename_wizard
  mesoSPIM_AcquisitionManagerWindow --> focus_tracking_wizard
  mesoSPIM_AcquisitionManagerWindow --> image_processing_wizard
  mesoSPIM_AcquisitionManagerWindow --> models
  mesoSPIM_AcquisitionManagerWindow --> multicolor_acquisition_wizard
  mesoSPIM_AcquisitionManagerWindow --> utility_functions
  mesoSPIM_AcquisitionManagerWindow --> widgets
  mesoSPIM_Camera --> hamamatsu
  mesoSPIM_Camera --> hamamatsu_camera
  mesoSPIM_Camera --> acquisitions
  mesoSPIM_CameraWindow --> optimization
  mesoSPIM_Core --> Demo_LaserEnabler
  mesoSPIM_Core --> mesoSPIM_LaserEnabler
  mesoSPIM_Core --> Demo_Shutter
  mesoSPIM_Core --> NI_Shutter
  mesoSPIM_Core --> mesoSPIM_Camera
  mesoSPIM_Core --> mesoSPIM_ImageWriter
  mesoSPIM_Core --> mesoSPIM_Serial
  mesoSPIM_Core --> mesoSPIM_WaveFormGenerator
  mesoSPIM_Core --> acquisitions
  mesoSPIM_Core --> utility_functions
  mesoSPIM_ImageWriter --> acquisitions
  mesoSPIM_ImageWriter --> utility_functions
  mesoSPIM_MainWindow --> WebcamWindow
  mesoSPIM_MainWindow --> mesoSPIM_JoystickHandlers
  mesoSPIM_MainWindow --> mesoSPIM_AcquisitionManagerWindow
  mesoSPIM_MainWindow --> mesoSPIM_CameraWindow
  mesoSPIM_MainWindow --> mesoSPIM_ContrastWindow
  mesoSPIM_MainWindow --> mesoSPIM_Core
  mesoSPIM_MainWindow --> mesoSPIM_Optimizer
  mesoSPIM_MainWindow --> mesoSPIM_ScriptWindow
  mesoSPIM_MainWindow --> mesoSPIM_State
  mesoSPIM_MainWindow --> mesoSPIM_TileViewWindow
  mesoSPIM_Optimizer --> optimization
  mesoSPIM_Serial --> mesoSPIM_FilterWheel
  mesoSPIM_Serial --> mesoSPIM_Stages
  mesoSPIM_Serial --> mesoSPIM_Zoom
  mesoSPIM_Stages --> asicontrol
  mesoSPIM_Stages --> galilcontrol
  mesoSPIM_State --> acquisitions
  mesoSPIM_WaveFormGenerator --> waveforms
  delegates --> widgets
  filename_wizard --> utility_functions
  models --> acquisitions
  multicolor_acquisition_builder --> acquisitions
  multicolor_acquisition_wizard --> filename_wizard
  multicolor_acquisition_wizard --> multicolor_acquisition_builder

```
