<!-- .slide: data-background-image="images/mirantis-logo.svg" data-background-size="auto 90%" -->


<!-- Slide -->
# 1
### OpenStack


<!-- Slide -->
###### Mirantis
###### OpenStack 9
with 

<img src="images/openstack/openstack-mitaka-logo-sm2.png" style="width:40%;">


<!-- Slide -->
Mirantis is the

### only 

distribution

not maintaining an own

### Base OS


<!-- Slide -->
#### Controller nodes
Ubuntu 14.04 (next 16.04)

<br>
#### Compute nodes <!-- .element class="fragment" data-fragment-index="1"-->
Ubuntu 14.04 (next 16.04) <!-- .element class="fragment" data-fragment-index="1"-->

RHEL 7.x <!-- .element class="fragment" data-fragment-index="1"-->

Oracle Linux 7.x <!-- .element class="fragment" data-fragment-index="1"-->

SUSE Enterprise Linux <!-- .element class="fragment" data-fragment-index="1"-->
Note: SUSE will provide also support for RHEL and CentOS


<!-- Slide -->
### Kernel
depends on Base OS

### Hypervisor
KVM 

Xen via plugin

VMWare vSphere


<!-- Slide -->
Deployment

via 
### Fuel


<!-- Slide -->
### Openstack Support

All Core Services plus

<table>
<tr>
    <td><img src="images/openstack/barbican-notsupported.svg"></td>
    <td><img src="images/openstack/ceilometer.svg"></td>
    <td><img src="images/openstack/designate-notsupported.svg"></td>
    <td><img src="images/openstack/fuel.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/heat.svg"></td>
    <td><img src="images/openstack/horizon.svg"></td>
    <td><img src="images/openstack/ironic.svg"></td>
    <td><img src="images/openstack/magnum-notsupported.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/manila-notsupported.svg"></td>
    <td><img src="images/openstack/mistral-notsupported.svg"></td>
    <td><img src="images/openstack/murano.svg"></td>
    <td><img src="images/openstack/sahara.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/tempest-notsupported.svg"></td>
    <td><img src="images/openstack/trove-notsupported.svg"></td>
    <td></td>
    <td><img src="images/openstack/legend.svg"></td>
</tr>
</table>


<!-- Slide -->
### Life Cycle 
New downstream version with 

###### every upstream release

within 1-6 months 

<br>
Next:

MOS 10 (Newton, H1/2017)
Note: MOS 9.1 (Mitaka Update, Oct. 2016)


<!-- Slide -->
Additionally recommended

### Mirantis Stacklight
and
### Partner Catalog
(Billing, LBaaS, DBaaS, SDN, Storage)


<!-- Slide -->
### Support
Each release for
###### 3 years


<!-- Slide -->
### Pricing

per machine (Ubuntu) 

per-socket-pair (RHEL)

<br>
##### depending on:

8x5

24x7

Proactive


<!-- Slide -->
# 2
## Ceph


<!-- Slide -->
Part of
### MOS

based on <!-- .element class="fragment" data-fragment-index="1"-->

### Hammer <!-- .element class="fragment" data-fragment-index="1"-->
and <!-- .element class="fragment" data-fragment-index="1"-->
### Ubuntu <!-- .element class="fragment" data-fragment-index="1"-->

Note: MOS v9.1 will stick with this version


<!-- Slide -->
Deployment via
### Fuel
plugin


<!-- Slide -->
Only
### RBD 
and
### RadosGW 
supported


<!-- Slide -->
## Pricing
Subscription

based on:

gross capacity
