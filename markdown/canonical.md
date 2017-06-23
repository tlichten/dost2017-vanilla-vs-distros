<!-- .slide: data-background-image="images/ubuntu-logo.svg" data-background-size="auto 90%" -->


<!-- Slide -->
# 1
### OpenStack


<!-- Slide -->
### Ubuntu
### OpenStack 
with

<img src="images/openstack/openstack-ocata-release-logo-480.png" style="width:15%;">

based on

`Ubuntu 16.04 LTS`


<!-- Slide -->
### Kernel
4.4-based

<br> 
### Hypervisor <!-- .element class="fragment" data-fragment-index="1"-->
KVM <!-- .element class="fragment" data-fragment-index="1"-->

Hyper-V <!-- .element class="fragment" data-fragment-index="1"-->

LXD <!-- .element class="fragment" data-fragment-index="1"-->


<!-- Slide -->
Let's get one thing out of the way!
<br>
<br>
### "Canonical" OpenStack <!-- .element class="fragment" data-fragment-index="2"-->
(enterprise version) <!-- .element class="fragment" data-fragment-index="5"-->
## ≠ <!-- .element class="fragment" data-fragment-index="3"-->
### Ubuntu OpenStack <!-- .element class="fragment" data-fragment-index="4"-->
(community version) <!-- .element class="fragment" data-fragment-index="5"-->


<!-- Slide -->
While probably most

`Community Developers`

using Ubuntu, make use of <!-- .element class="fragment" data-fragment-index="1"-->

`DevStack, Puppet, Ansible, Chef` <!-- .element class="fragment" data-fragment-index="1"-->

the enterprise version uses<!-- .element class="fragment" data-fragment-index="2"-->

###### JuJu and MaaS <!-- .element class="fragment" data-fragment-index="2"-->


<!-- Slide -->
### Openstack Support

All Core Services plus

<table>
<tr>
    <td><img src="images/openstack/aodh-notsupported.svg"></td>
    <td><img src="images/openstack/barbican-techpreview.svg"></td>
    <td><img src="images/openstack/ceilometer.svg"></td>
    <td><img src="images/openstack/designate-techpreview.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/gnocchi-notsupported.svg"></td>
    <td><img src="images/openstack/heat-techpreview.svg"></td>
    <td><img src="images/openstack/horizon.svg"></td>
    <td><img src="images/openstack/ironic-techpreview.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/magnum-techpreview.svg"></td>
    <td><img src="images/openstack/manila-techpreview.svg"></td>
    <td><img src="images/openstack/mistral-techpreview.svg"></td>
    <td><img src="images/openstack/monasca-notsupported.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/murano-techpreview.svg"></td>
    <td><img src="images/openstack/panko-notsupported.svg"></td>
    <td><img src="images/openstack/rally-techpreview.svg"></td>
    <td><img src="images/openstack/sahara-techpreview.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/tempest-techpreview.svg"></td>
    <td><img src="images/openstack/trove-techpreview.svg"></td>
    <td></td>
    <td><img src="images/openstack/legend.svg"></td>
</tr>
</table>


<!-- Slide -->
### Life Cycle 
New downstream version with 

###### every upstream release


<!-- Slide -->
Additionally recommended

### Landscape
for

system management, security compliance and audit


<!-- Slide -->
### Support
###### 5 years
For versions released with LTS
###### 1,5 years
For 3 following versions (e.g. N, O, P)
###### 3 years
OpenStack release of next LTS in former version

Note: quite complex matrix. ocata only supported 1.5 years


<!-- Slide -->
### Pricing

node/year

VM/hour

OpenStack regions (S/M/L)

<br>
##### depending on:

support for business hours, 24x7, managed


<!-- Slide -->
# 2
### Ceph


<!-- Slide -->
### Ubuntu Advantage Storage

based on 

### Jewel

with

`Ubuntu Performance Dashboard` and `OpenAttic`


<!-- Slide -->
###### CephFS
###### iSCSI
no Juju charm


<!-- Slide -->
## Pricing

Subscription

based on:

used capacity

Note: Yearly subscriptions?


<!-- Slide -->
# 3
### Potential Issues


<!-- Slide -->
### Landscape
and <!-- .element class="fragment" data-fragment-index="1"-->
### Ubuntu Performance Dashboard <!-- .element class="fragment" data-fragment-index="1"-->
(for Ceph) <!-- .element class="fragment" data-fragment-index="1"-->

have a <!-- .element class="fragment" data-fragment-index="2"-->

`non Open Source license` <!-- .element class="fragment" data-fragment-index="2"-->


<!-- Slide -->
## Kernel
At least <!-- .element class="fragment" data-fragment-index="1"-->

controversial <!-- .element class="fragment" data-fragment-index="1"-->

integration of <!-- .element class="fragment" data-fragment-index="1"-->

## ZFS <!-- .element class="fragment" data-fragment-index="2"-->
in 16.04 <!-- .element class="fragment" data-fragment-index="2"-->

