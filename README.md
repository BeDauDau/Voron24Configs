# VORON 2.4  

My 3D Printer Backup Config

- SHEET METAL MONOLITH GANTRY AWD
- DOOMCUBE
- DK's TOOLHEAD

# TREE STRUCTURE
```
Voron24Configs/
├── 📄 Core Configuration Files
│   ├── printer.cfg                    # Main printer configuration
│   ├── config_backup.cfg              # Backup of printer config
│   ├── chopper_tune.cfg               # Motor chopper tuning settings
│   ├── KAMP_Settings.cfg              # Klipper Adaptive Mesh Purge settings
│   ├── KlipperScreen.conf             # KlipperScreen UI configuration
│   ├── moonraker.conf                 # Moonraker API server config
│   ├── moonraker.conf.backup          # Moonraker backup config
│   ├── crowsnest.conf                 # Webcam streamer configuration
│   ├── sonar.conf                     # Sonar configuration (if used)
│   ├── timelapse.cfg                  # Timelapse video settings
│   └── autocommit.sh                  # Auto-commit script for backups
│
├── 📁 MACHINE/                        # Hardware-specific configurations
│   ├── machine.cfg                    # Main machine configuration
│   ├── Fysetc_Spider_v3.x.cfg        # Control board (Fysetc Spider v3)
│   ├── xy_steppers.cfg                # XY stepper motor configuration
│   ├── z_steppers.cfg                 # Z-axis stepper motors
│   ├── extruder.cfg                   # Extruder and hotend settings
│   ├── heater_bed.cfg                 # Heated bed configuration
│   ├── Cartographer.cfg               # Cartographer bed probe settings
│   ├── klipperExpander.cfg            # GPIO expander configuration
│   └── pitb.cfg                       # PITB (Probe in Toolhead Board) config
│
├── 📁 MACROS/                         # Custom printer macros
│   ├── macros.cfg                     # Main macros file
│   ├── bedfans.cfg                    # Bed fan control macros
│   ├── nozzle_scrub.cfg               # Nozzle scrubbing routine
│   ├── sensorless.cfg                 # Sensorless homing configuration
│   ├── mpc.cfg                        # Model Predictive Control tuning
│   └── test_speed.cfg                 # Speed testing macro
│
├── 📁 KAMP/                           # Klipper Adaptive Mesh Purge addon
│   ├── readme.md                      # KAMP documentation
│   ├── Adaptive_Mesh.cfg              # Adaptive bed mesh configuration
│   ├── Line_Purge.cfg                 # Line purge pattern
│   ├── Voron_Purge.cfg                # Voron-specific purge pattern
│   ├── Simplify3D_Fix.cfg             # Simplify3D compatibility fix
│   └── 📁 Configuration/              # KAMP sub-configurations
│       ├── Adaptive_Meshing.cfg
│       ├── KAMP_Settings.cfg
│       ├── Line_Purge.cfg
│       ├── Smart_Park.cfg
│       └── Voron_Purge.cfg
│
├── 📁 adxl_results/                   # Motors Chopper calibration data 
│
├── 📁 ShakeTune_results/              # ShakeTune vibration analysis data
│   ├── 📁 axes_map/                   # Axes mapping calibration
│   │   └── axesmap_*.png              # Axes map visualization images
│   ├── 📁 belts/                      # Belt tension analysis
│   ├── 📁 input_shaper/               # Input shaper tuning results
│   └── 📁 vibrations/                 # Vibration analysis data
│
├── 📁 NOT_USE/                        # Deprecated/unused configurations
│   └── Nyoomies.cfg                   # Unused acceleration macro
│
├── 📁 .theme/                         # KlipperScreen theme files
│
├── 📄 README.md                       # This documentation
├── .gitignore                         # Git ignore rules
└── Database & Temporary Files
    ├── moonraker-sql.db               # Moonraker database
    ├── .moonraker.conf.bkp            # Moonraker backup
    └── calibration_data_fan_*.png     # Fan calibration images
```
