^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cpr_indoornav_jackal
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.3.4 (2022-11-24)
------------------
* Use a 30-sample rolling average for the battery percentage instead of single samples. On Jackal this equates to ~30s averages
* Add a group for wireless charge docking if applicable
* Reduce the upper limit for the full battery voltage to 28.8V. See OPG02-76
* Contributors: Chris Iverach-Brereton

0.3.3 (2022-10-03)
------------------
* Add separate bridge params for GX5 vs UM7 setups
* Add the web GUI input to the twist_mux
* tune dock distance without actual receiver attached
* added launch file for docking. added argument to create docking job
* remove controller launch
* made hokuyo the default laser
* added dock controller launch file
* added section to start indoornav docking and docking setup script
* Contributors: Chris Iverach-Brereton, José Mastrangelo

0.3.2 (2022-07-28)
------------------
* Fix the python interpreter to force python3
* Contributors: Chris Iverach-Brereton

0.3.1 (2022-06-03)
------------------
* Change the ROS1->2 bridge domain to 91
* Fix a bug with the BRIDGE_SETUP_PATH envar
* Contributors: Chris Iverach-Brereton

0.3.0 (2022-05-06)
------------------
* Initial public release
* Contributors: Chris Iverach-Brereton
