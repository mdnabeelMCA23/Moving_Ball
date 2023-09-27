#Moving_Ball
The bouncing ball itself is represented by a <div> element with the id="ball". This <div> has inline CSS styles applied to it, setting its color, initial position, shape, and size.

CODE STRUCTURE:
Variables like velocity, position, ball, end, position_1, and direction are defined to control the animation.
velocity determines the speed of the ball's movement.
position keeps track of the current position of the ball.
end sets the maximum position where the ball should bounce.
position_1 and direction control the ball's direction.
The move function updates the position based on velocity and direction. It also handles bouncing logic, changing the direction when the ball reaches the end or its initial position.
Finally, setInterval(move, 100); is used to call the move function every 100 milliseconds, creating the bouncing animation effect.

Done By
[Mohammed Nabeel P]
