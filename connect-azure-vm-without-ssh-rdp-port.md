When you open **PORT 22 for SSH** or **3389 for RDP** in your Azure VM.

You are fundamentally taking a risk.

You are exposing your VM from public attacks!

As the IP is public, the attacker is just going to run the scripts!

But for early stage startups, small companies this can be a big security loophole and for big companies, this is a major compliance issue!

While early stage startups cannot afford compliance and auditing firms!

They are putting their resources and assets as risk!

Is there a solution to it?

Don't open them?

Yes, this is one solution! If you don't want to access to your VM after creating them!

But I want to access them!

Well in that can you can use [Azure Bastion](https://docs.microsoft.com/en-us/azure/bastion/bastion-overview)

It is a **PAID** service by Microsoft Azure, where you can still access your VM without opening those ports!

All you need is your Microsoft Azure Account and Browser!

![Credits: Azure Docs](https://user-images.githubusercontent.com/4149253/149535702-35dd482a-d768-4727-b375-28733548d262.png)
