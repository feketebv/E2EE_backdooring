# Law enforcing end-to-end asymmetric encryption key agreement scheme
A protocol capable of individually backdooring E2E encrypted secret communication for use by multiple independent state authorities.

Its operation is as follows:
* first the parties who wish to communicate, establish key agreements with their dedicated local authorities' servers
* then they apply the key values agreed upon with the diverse authorities as the final key agreement's secret values inbetween the two of them

# Properties
* creates 2 sets of backdoor keys for authorities on both ends of the communication channel
* one set of such authorities can only re-generate the cryptographical keys for the channel, if all of them agree to the eavesdropping and share their portions of the initial key agreement

# Some possible variants
* over 2 set of authorities for group communication applications
* elliptic curve multiplication based Diffie-Hellman instead of modular exponentiation
* hashing of sub key results with authority sets for example to decrease the number of Diffie-Hellman computations

# On why this piece of intellectual property is not for sale and is prohibited from being used based on my copyrights
As long as powers in a liberal democracy can be _securely_ separated, sheer theoretically it is possible, that only dedicated people get eavesdropped, whose communication raises established suspition of breaking _useful_ laws. As the author and inventor of this protocol I do not believe currently in the security of power branch separations in the free world being safe enough, but I do believe that privacy is a basic human right which needs utmost protection. Privacy is so elementary among others, because data mining enables fine tuned manipulation and law making that have never been seen before and artificial intelligence will or already poses a threat of spreading unprecedented amounts of fake information, which both methods get even more efficient if people's communication can be monitored and used as feedback for such processes.

https://www.ft.com/content/78ba92ed-94ef-47ce-9157-658e068cd814
https://www.ft.com/content/67e6263d-f938-44f6-830f-f0a86542f215
