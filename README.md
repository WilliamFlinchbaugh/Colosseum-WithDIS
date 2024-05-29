# Colosseum With DIS Support!

The updates to this plugin:

- The [AF-GRILL DIS Plugin](https://github.com/AF-GRILL/DISPluginForUnreal/tree/ue5) is now a dependency (found in Unreal/Plugins/AirSim/AirSim.uplugin and in Unreal/Plugins/AirSim/Source/AirSim.build.cs)
- The DISSendComponent from the DIS Plugin is now added to the Multirotor "Flying Pawn" and it is set to send Entity State PDUs every 0.25 seconds (found in Unreal/Plugins/AirSim/Source/Vehicles/Multirotor/FlyingPawn.h/.cpp)

This can easily be changed, and you could definitely add this component to the car using essentially the same code.

Hope this helps!
