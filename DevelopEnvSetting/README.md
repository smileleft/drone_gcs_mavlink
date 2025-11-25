# Development Env Setting

## PX4 SITL

```bash
# PX4 source code
git clone https://github.com/PX4/PX4-Autopilot.git --recursive

# Install Dependency
./Tools/setup/ubuntu.sh

# Run SITL
HEADLESS=1 make px4_sitl gz_x500

# check status
pxh> commander status
pxh> listener sensor_combined
pxh> listener vehicle_attitude
```

## Connect QGroundControl
