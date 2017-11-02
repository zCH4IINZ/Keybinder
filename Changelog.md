# Keybinder - Changelog
if(GetVehicleLockState() == 0)

SendChat("/lock")
if(GetVehicleEngineState() == 0)
SendChat("/motor")
# Test 
