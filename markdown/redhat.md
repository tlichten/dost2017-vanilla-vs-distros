<!-- .slide: data-background-image="images/redhat-logo.svg" data-background-size="90% auto" -->


<!-- Slide -->
# 1
### OpenStack 


<!-- Slide -->
###### Red Hat 
###### OpenStack Platform 11
with

<img src="images/openstack/openstack-ocata-release-logo-480.png" style="width:15%;">

based on

`RHEL 7.3`


<!-- Slide -->
### Kernel
3.10-based

<br>
### Hypervisor <!-- .element class="fragment" data-fragment-index="1"-->
KVM<!-- .element class="fragment" data-fragment-index="1"-->

ESX (vCenter)<!-- .element class="fragment" data-fragment-index="1"-->

Note: Kernel API/ABI compatibility


<!-- Slide -->
Deployment

## OSP director
TripleO/Ironic and Ansible (optional)

or

### Packstack
for test environments


<!-- Slide -->
### Openstack Support

All Core Services plus

<table>
<tr>
    <td><img src="images/openstack/aodh.svg"></td>
    <td><img src="images/openstack/barbican-notsupported.svg"></td>
    <td><img src="images/openstack/ceilometer.svg"></td>
    <td><img src="images/openstack/designate-techpreview.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/gnocchi.svg"></td>
    <td><img src="images/openstack/heat.svg"></td>
    <td><img src="images/openstack/horizon.svg"></td>
    <td><img src="images/openstack/ironic.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/magnum-notsupported.svg"></td>
    <td><img src="images/openstack/manila.svg"></td>
    <td><img src="images/openstack/mistral-notsupported.svg"></td>
    <td><img src="images/openstack/monasca-notsupported.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/murano-notsupported.svg"></td>
    <td><img src="images/openstack/panko.svg"></td>
    <td><img src="images/openstack/rally-techpreview.svg"></td>
    <td><img src="images/openstack/sahara.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/tempest.svg"></td>
    <td><img src="images/openstack/trove-notsupported.svg"></td>
    <td></td>
    <td><img src="images/openstack/legend.svg"></td>
</tr>
</table>

Note: source https://access.redhat.com/articles/1535373


<!-- Slide -->
### Life Cycle 
New downstream version with

###### every upstream release

Next:

Pike


<!-- Slide -->
Additionally recommended

### OSP director
### Satellite
### CloudForms (bundled)


<!-- Slide -->
### Support
betwen
###### 1 year 
(phase 2 support, like r11) 

and 

###### up to 5 years
(LLR/LTS releases like r10)

Note: release 11 is no LTS release, https://access.redhat.com/support/policy/updates/openstack/platform, No feature backport or new partner additions


<!-- Slide -->
### Pricing

per machine and per-socket-pair

<br>
##### depending on:

running RHEL guests or not

support for business hours or 24x7

special SLAs


<!-- Slide -->
# 2
## Ceph


<!-- Slide -->
###### Red Hat Ceph Storage 2.3

based on

### Jewel
RHEL 7.3 or Ubuntu 16.04


<!-- Slide -->
Deployment via
### RH Storage Console
or
### Ansible
or
### manually


<!-- Slide -->
###### CephFS
Tech preview (Support planed for 3.0)
###### NFS
via Object Gateway
###### iSCSI
Tech preview


<!-- Slide -->
## Pricing

Yearly subscriptions

based on:

raw capacity with node limit

Also available: <!-- .element class="fragment" data-fragment-index="1"-->

pre-production subscriptions <!-- .element class="fragment" data-fragment-index="1"-->

Note: unlimited Pre-Production subscription for fix price under 5000 Dollar.

