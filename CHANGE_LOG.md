# Surface Mounted Lights :: Change Log

* 2016-0508: 1.2.3.alpha3 (IgorZ) for KSP 1.1 PRE-RELEASE
	+ Cumulative pre-release changes:
		- [Change] Minor code adjustments to compile under KSP 1.1
		- [Change] Disable animation on 4-way light since it doesn't work properly anyways.
		- [Change] Rename GUI action and event names in 4-way light to identify which light they control.
		- [Internal] Create a multipoint light module and use it in 4-way light.
		- [Internal] Migrate spot and omni lights to the stock LightModule.
		- [Internal] Drop incomplete SurfaceNavLight module.
		- [Internal] Drop unused SurfaceLight module.
		- [Internal] Rename multi point light module to a more KSP name.
		- [Internal] Improve reliability of multi point light module when config paremetrs or model are bad.
		- [Internal] Create a new module based on old SurfaceLight to support colored lens on the light.
		- [Change] Expose setting "Lens brightness" to allow customizing light's minimum brightness level.
* 2016-0506: 1.2.3.alpha2 (IgorZ) for KSP 1.1 PRE-RELEASE
	+ Pre-release changes:
		- [Change] Minor code adjustments to compile under KSP 1.1
		- [Change] Disable animation on 4-way light since it doesn't work properly anyways.
		- [Change] Rename GUI action and event names in 4-way light to identify which light they control.
		- [Internal] Create a multipoint light modulde and use it in 4-2ay light.
		- [Internal] Migrate spot and omny lights to the stock LightModule.
		- [Internal] Drop incomplete SurfaceNavLight module.
		- [Internal] Drop unused SurfaceLight module.
* 2016-0504: 1.2.3.alpha1 (IgorZ) for KSP 1.1 PRE-RELEASE
	+ Minor code adjustments to compile under KSP 1.1
* 2016-0514: 1.2.3 (IgorZ) for KSP 1.1
	+ 1.2.3 (May 13, 2016):
		- [Change] Code adjustments to compile under KSP 1.1.2
		- [Change] Disable animation on 4-way light since it doesn't work properly anyways.
		- [Change] Rename GUI action and event names in 4-way light to identify which light they control.
		- [Change] Expose setting "Lens brightness" to allow customizing light's minimum brightness level.
* 2015-1116: 1.2.2 (Why485) for KSP 1.0.5
	+ <small class="text text-muted">Released on 2015-11-15</small>
		- Fixed bug where light color was not correctly restored when loading a ship in the editor.
		- Refactored code for expansion (future development of navlights)
* 2015-1113: 1.2.1 (Why485) for KSP 1.0.5
	+ No changelog provided
