---
title : 'VPS Compliance'
---

# VPS Compliance

### Information Regarding SGX Compliance for VPS options and the Secret Network

This is intended to guide you in selecting SGX compliant VPS options for the Secret Network mainnet.

Note. When renting a compliant bare metal machine from a VPS provider, ensure you do not accept any chassis or CPU substitutes they propose, unless those substitutes are on the [Hardware Compliance list.](https://docs.scrt.network/node-guides/hardware-compliance.html)


#### Microsoft Azure Confidential Computing

Microsoft Azure is tested and confirmed working by the Secret Network Community.

To setup a node on Microsoft Azure do the following.

1. Visit the Azure Confidental Compute page [here](https://azure.microsoft.com/en-us/solutions/confidential-compute/) and click "Get Started"
2. Click "Get it now" on the following page and signup for a Microsoft Azure Account.
3. While provisioning your VPS be sure to have at least 250GB of premium SSD storage available.
4. After your confidential compute VM is deployed, continue with the node setup guide [starting here.](https://build.scrt.network/validators-and-full-nodes/run-full-node-mainnet.html)

#### Psychz

Coming Soon.

#### nforce

Coming soon.

#### leaseweb

Leaseweb has been tested and confirmed working by the Secret Network community.

1. Rent a [VPS from them](https://www.leaseweb.com/dedicated-servers/build-your-own) with any of the hardware that shows as working on the [Hardware Compliance list](https://docs.scrt.network/node-guides/hardware-compliance.html).
2. Ensure that Hyperthreading & overclocking/undervolting are disabled in the bios.
3. [Install SGX](https://docs.scrt.network/node-guides/setup-sgx.html).
4. Continue with the node setup guide [starting here.](https://build.scrt.network/validators-and-full-nodes/run-full-node-mainnet.html)

##### Contributers


