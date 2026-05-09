## Navigation Strategy

Our robot is designed to complete a full loop around the competition track while making correct navigation decisions. Because the track does not contain continuous guiding lines, the robot cannot rely on traditional line-following methods.

Instead, our main navigation strategy is based on maintaining a stable distance from the outer wall using distance sensors. This allows the robot to follow the shape of the track and remain stable while moving.

The robot will also use a front-facing color sensor to detect the colored poles placed on the track. When a pole is detected, the robot will decide which direction to turn in order to avoid it and then return to its normal navigation mode.

The robot will use two distance sensors, one color sensor, and rear wheel drive with front wheel steering. The mechanical design will be slim and lightweight to allow fast and stable movement through the track.
