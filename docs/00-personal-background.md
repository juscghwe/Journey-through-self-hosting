<details>
<summary>Personnal background</summary>

Every homelab is shaped by the person running it.

- Some people run hundreds of containers with a near zero-touch approach.
- Others prefer small, carefully curated setups that grow slowly over time.
- And then there’s always someone with a server rack worth more than my car.

This is where I come from:

Up until the second half of 2025, I never really *got* homelabbing.

I had seen some of Jeff Geerling's content ([Github](https://github.com/geerlingguy) | [YouTube](https://www.youtube.com/c/JeffGeerling)), but that was about it. To me, homelabbing looked like an expensive hobby focused on running third-party software and making network cabinets look good on Reddit.

That said, I do have some background in self-taught software development. I've always been curious about what happens *behind* the  code - infrastructure, networks, deployment and failure modes. I just didn't know how all of that would ever matter to me.

Until it did.

### The Homematic incident

The moment everything clicked for me was during the setup of a *HomeMaticIP Access Point*.

Like with many new devices, things didn't work immediately. While troubleshooting, the manual suggested opening a port on my router. At the time, I was inexperienced and didn't fully understand what that meant.

I followed the instructions.

In doing so, I accidentally - and unknowingly - exposed an unprotected service to the entire internet. All of that, just so I could change the temperature of my thermostats.

That was my first real "*oh… this is what infrastructure actually means*" moment.

### The inconvenience of "smart" homes

I'm not a big fan of smart homes - at least not in their current, consumer-ready form. 

In my opinion
- Every **digital** product should work without a permanent internet connection.
- Every **analog** product should work without digital infrastructure.
Most smart home devices do neither.

Instead, you end up with:
- Dozens of accounts
- Multiple apps for different devices
- Devices that can't talk to each other in a meaningful way despite beeing "Alexa-compatible" or "Google Home-ready"
On top of that, many vendors charge you recurring fees for features your own hardware is already capable of.

I have surveillance cameras with built-in AI chips - yet object detection and notifications are locked behind a subscription.

At the same time, we're used to "owning" digital products that we don't actually own. Movies bought at full DVD or Blu-ray prices on streaming platforms can disappear at any time.

You pay - but control and ownership stays elsewhere. 

### My personal goal

From that point on, my goals become fairly clear:

- [ ] No exposure without full controll over what is exposed
- [ ] Every digital system mustwork when the ISP connection is down
- [ ] Every analog system must work without digital services
- [ ] My data, my services and my products belong to me
- [ ] No unnecessary e-waste or sudden vendor rug-pulls

### The costs of self-hosting
I can't afford enterprise-grade setups or harware - and I don't want to.

I’m lucky enough to have a close relative working in IT, which means I occasionally get access to used hardware that would otherwise be thrown away. Apart from that, my setup relies on:
- Old PC-parts from my basement
- eBay finds
- Making things work even when they don't want to
- Constantly monitoring resource usage

The cost of my homelab should support learning - never endanger my quality of life.

At the end of the day, freedom of choice isn’t worth much if it comes at the cost of financial stress.

</details>