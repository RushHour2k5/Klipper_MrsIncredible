# Mrs. Incredible (M600) macro for Klipper. Based on <a href="https://www.reddit.com/user/Lexx3D">u/Lexx3D's</a> <a href="https://www.reddit.com/r/klippers/comments/m57iai/mom_my_overpowered_m600_command/?utm_source=share&utm_medium=web2x&context=3">MOM (My Overpowered M600)</a> macro.

Install as you would normally a Klipper Macro file.

04/29/2022 v0.4.0
Corrected bug with slow_load_length being called for feedrate instead of slow_load_feedrate.

04/29/2022 v0.3.5
Corrected bug with missing spaces causing LOW_TEMP_CHECK macro not to load.

04/29/2022 v0.3.4
Corrected bug with fans_on not being called by JOBCENTER.

04/29/2022 v0.3.3
Corrected bug for fans variable overwriting the cool variable.

04/26/2022 v0.3.2
Removed call for variable in HTML UI and added a missing variable for Z_feedrate in m600cfg.

04/26/2022 v0.3.1
Corrected variables to use full math calculations for acceleration and feedrates.

04/26/2022 v0.3.0
Source code rewritten by <a href="https://www.reddit.com/user/RushHour2k5">r/RushHour2k5</a> to mimic Marlin's Advanced Pause Feature.

04/26/2022 v0.2.0 (initial commit by <a href="https://www.reddit.com/user/RushHour2k5">r/RushHour2k5</a>)
Souce code updated to work with LONGER LK5 Pro using Marlin 2.0 values.

09/11/2021 v0.1.6 (by <a href="https://www.reddit.com/user/Lexx3D">u/Lexx3D</a>)
Source code maintenance due to Klipper updates.

XX/XX/XXXX v0.1.5 (by <a href="https://www.reddit.com/user/Lexx3D">u/Lexx3D</a>)
Added ability to prevent nozzle cooldown.
