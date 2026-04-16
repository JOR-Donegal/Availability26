# Engineering Reliability

As assemblies became more complex, some of the realities of modern dependability engineering became obvious. Reliability is based on the concept of a mission. An airplane takes off and flies for 6 hours, Dublin to New York. We cannot accept failure during the mission, but we can test, repair and maintain at the end of a mission. Where:

The failure of a single component will cause the failure of the systems

Components have a predictable failure rate (λ)

There is a defined mission time (t)

Then an assembly’s reliability may be modelled using an exponential reliability equation as

<figure>
<img src = "https://jor-donegal.github.io/Availability26/images/eq1.jpg">
<figcaption>Eq 1. Reliability.</figcaption>
</figure>

As a system becomes more complex in terms of component count (n), the probability of the system operating correctly rapidly diminishes; this conclusion will be revisited many times. In designing critical infrastructure, component count can be kept low, MILSPEC components with very low λ can be used at great expense, or the mission time may be minimized. The early pioneers of vacuum tube computing learned a truism often quoted today; __complexity is the enemy of reliability__.

<figure>
<img src = "https://jor-donegal.github.io/Availability26/images/graph1.jpg">
<figcaption>Graph 1. Reliability.</figcaption>
</figure>