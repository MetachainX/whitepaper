The concept of space refers to the three-dimensional extent in which all physical objects and entities exist. It is the framework that holds everything in the universe, including spaceships, planets, asteroids, anomalies, and beings.

Objects within space are fixed and immutable, meaning they do not change their location. However, spaceships are capable of traveling through space, allowing them to explore and discover new areas within the universe.

---

The space within the universe is constantly expanding outwards from a central point known as the **genesis point**. As the distance from the genesis point increases, the difficulty of the world and the rewards that can be obtained also increase. 

Distant planets, for example, offer better rewards for users but also present a greater challenge due to the presence of more powerful enemies and other obstacles.

---

**Astronomical Unit (AU)** is a unit of distance measurement used in this space. It is defined as the average distance between the Earth and the Sun and is commonly used to measure distances within the solar system. However, in this context, it is used to measure the distances between different objects and locations within the universe.

Overall, space is an essential component of the universe and provides the framework within which all physical objects exist. The concept of space within this context also includes the notion of distance.

---

Objects are represented as a **three-dimensional array** of uint256 values, enabling us to locate any object within the space. It is known as Point.

**Point** is constructed using 3 values: X,Y,Z;

| Variable | Value Type | Min Value | Max Value |
| --- | --- | --- | --- |
| X | uint256 | 0 | uint256.max |
| Y | uint256 | 0 | uint256.max |
| Z | uint256 | 0 | uint256.max |

<aside>
💡 Example: Bobs' Spaceship location is Point(123,222,333), thus representing X = 123, Y = 222, Z = 333;

</aside>

---

Space is a static object that serves only one purpose, which is to hold other objects, and does not interact with them. It represent a state of this world at current time **T**.

To change the state of this world, we use interactions defined in other mechanics to manipulate the space and move objects to new locations within it.

The limitations of space are solely determined by the programming language and game mechanics, as space itself does not inherently impose any limitations.

---

**Genesis Point** is a starting point from which this world expanded. It is used for calculations in game mechanics to determine things like planet level, enemy strength, spawn points for new players.

World expands outwards at rate determined in Word Laws. This rate can be changed in order to increase or decrease game expansion speed.

---

This space is initially empty and is gradually populated with objects.

Space hold any type of object.

There is only one space per world.
