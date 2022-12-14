[]{#anchor}**Cybersecurity Challenges and Considerations of 5G.**

"For every lock, there is someone out there trying to pick it or break
it." David Bernstein.

![](Pictures/100000000000037000000294F2CEFCEFDE4D1D48.jpg){width="6.5in"
height="4.8752in"}

Have you felt the importance of the Internet of Things in your everyday
life? I bet you have, and probably you enjoy every bit of it.
Connectivity is not just luxurious but a very essential part of today\'s
life. These technologies interact to create a flurry of interconnections
previously unimagined. Heaven knows how connected we are going to be
subsequently.

5G\'s immeasurable benefits such as increased efficiency, enhanced
mobile broadband, low latency, and massive machine-type communication
are a boon to businesses, industries, and consumers. In spite, of these
technological advancements, cybersecurity experts warn of robust and
evolving security challenges for emerging 5G networks.

Cybersecurity is the practice of ensuring computing systems or devices
accessible over the internet are safe from malicious threats and
attacks.

A review of the evolution of wireless technologies is helpful in fully
grasping the essence of 5G. 1G, introduced in the early 1980s, had
analog voice communication at its core. The poor quality of the voice
transmission necessitated the transition to 2G in the 90s, bringing
about digital encoding and transmission of voice data as well as a text
messaging feature known today as SMS. The 3G network was the pioneer of
multimedia communication, integrating voice, video, data, or multimedia.
This led to the deterioration in indoor connectivity that consequently
landed us at 4G.

Enter 5G, the fifth generation of wireless or cellular internet
technology. It features faster data-transfer rates and simultaneous
active connections without lags, as well as support for multiple devices
with diverse technologies, like sensors and smartphones.

Each new technology introduced a significant change toward meeting the
demerits of its predecessors.

[]{#anchor-1}5G's Evolving Threat Landscape/Attack Surface:

[]{#anchor-2}1. Software-Defined Networking and Network Function
Virtualization.

The defining feature of 5G technology is its novel shift from
centralized, hardware-based switching to distributed, Software-defined
Networking (SDN) that enables Network Function Virtualization (NFV). SDN
solves the traditional networking challenges brought about by
proprietary hardware components and their incompatibility issues. For
instance, it was difficult to integrate Cisco and Huawei devices into
one network infrastructure as both speak their proprietary languages.
These physical devices performing higher-level network functions
provided hardware choke points that simplified cyber hygiene
implementations. 5G implementation virtualizes these functions in
software. What does this mean for security? A new attack surface arises
and, thus, a need for more complex approaches to security. Should an
attacker gain control of the software managing the network, the attacker
is also able to control the
network.![](Pictures/1000000000000152000000E18719EB7C6BC18BD4.jpg){width="6.2992in"
height="4.1929in"}

[]{#anchor-3}2. Physical Infrastructure.

5G implements the use of millimeter wave spectrum, offering higher
frequencies as compared to traditional radio waves. The wavelength
ranges from 1 mm to 10 mm, while, traditional radio waves are longer and
in the range of tens of centimeters. Despite ensuring high speeds and
low latency, a major drawback is that these, 5G wavelengths can\'t
penetrate obstacles such as walls. They also can\'t travel long
distances. It, therefore, calls for the use of new technological
infrastructure and hardware such as handsets and small cells to
complement the cellular transmitters and increase the overall coverage.
These will be prone to physical and natural phenomena like natural
disasters, theft, power failures, and outages. Thus, the physical attack
surface increases significantly, and given the number of critical
systems and IoT devices, running on 5G networks, a failure of these
hardware infrastructures could be catastrophic.

[]{#anchor-4}3. Increased Attack Avenues.

Even though 5G is subject to the many existing cybersecurity risks, it
will also be susceptible to fresh cyber risks. Millions of vulnerable
devices connected to the 5G network position cyber hackers to attack a
very diverse threat landscape. This includes but is not limited to
transport networks, autonomous cars, and smart homes. This potential to
interconnect a massive number of devices will call for more vigilance in
securing the network, since, most of these interconnected devices will
be potential entry points for the malicious actor.

[]{#anchor-5}4. 5G Service Provider Threats.

5G technology roll-out is yet to take root and receive massive
acceptance. Very few service providers currently offer 5G. This means
that, though hypothetical, the threat of compromised hardware or
software rolled out by vendors compromised by state actors or otherwise
is real. This opens up a supply-chain attack vector that may be hard to
mitigate. A threat such as this, occurring in the initial roll-out
stages or during scheduled maintenance or updates, will go unnoticed by
a normal end-user.

[]{#anchor-6}5G mitigations against the above threats:

The above discourse only scratches the surface of the world of
unforeseen threats that cybersecurity experts, and users, have to
continuously guard against. Many more threats yet untouched, though, the
same mitigation measures as traditional threats, of current and previous
technologies will apply in most cases.

That said, here are some novel mitigation measures employed by 5G
network providers.

[]{#anchor-7}Multi-tier Networks/Network Slicing.

Network function virtualization allows for network slicing. The creation
of several virtual networks within the same shared physical
infrastructure has become possible. This entails the use of diverse
frequencies for the given interconnected devices. The frequency
classification is either low, medium, or high, with each delivering
specialized speeds and ranges. This implementation ensures that diverse
interconnected devices receive customized connections services such as
bandwidth speed, power consumption as well as latency. Most vendors have
embraced this as it helps them provide fine-tuned services. If well
implemented, this helps reduce the network attack surface, as it implies
that a compromised slice does not affect other network slices.

[]{#anchor-8}Zero-Trust.

This is an implementation that leverages the use of access control
policies. Initially employing the \"deny all\" policy and then opening
up accesses by the \"the least privilege\" significantly reduces
third-party risks to the network. This security model covers the
following areas:

-   Physical- encompasses aspects such as hardware, OEM certificate
    auditing establishing a supply chain trust from the IC\'s
    manufacturers.\
-   Logical- this entails stack-based software code signing and
    licensing features.\
-   Operational- continuous monitoring and evaluation of the virtualized
    and physical infrastructure, especially if the virtual or
    cloud-based infrastructure is third-party owned.

[]{#anchor-9}Open-source software.

Peer-reviewed and tested, publicly available source code, makes for more
secure code than the closed source, as vulnerabilities get noticed early
and are patched quickly. Closed-source tends towards security by
obscurity, which is quite unreliable.

[]{#anchor-10}Threat Intelligence in 5G.

While not entirely a new concept, 5G inherently provides greater
capabilities to leverage the use of threat intelligence in securing and
protecting networks. The evolution of threat intelligence from the
traditional static configurations, to reactive incidence response and
now the more robust predictive approach to security, is sufficient
reason for its adoption in 5G networks. This is because the many attack
vectors and the wide threat landscape require a more proactive approach
than a reactive one.

[]{#anchor-11}Bottom line

The fundamental shift in architecture and technology, the very novel
features that make for the robustness of 5G also open it up to new
attack vectors and continue to widen its threat landscape. These new
features if well implemented will greatly aid cyber defenders and level
up the playing field. 5G from the onset focuses on security by intent
and not as an afterthought. Let\'s watch and learn how its
implementation will work out.

[]{#anchor-12}References:

1.  [*https://www.verizon.com/about/our-company/5g/what-5g*](https://www.verizon.com/about/our-company/5g/what-5g)
2.  [*https://www.qualcomm.com/5g/what-is-5g/*](https://www.qualcomm.com/5g/what-is-5g/)
