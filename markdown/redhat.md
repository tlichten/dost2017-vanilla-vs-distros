<!-- .slide: data-background-image="images/redhat-logo.svg" data-background-size="90% auto" -->


<!-- Slide -->
# 1
### OpenStack 


<!-- Slide -->
###### Red Hat 
###### OpenStack Platform 9 
with

<img src="images/openstack/openstack-mitaka-logo-sm2.png" style="width:40%;">

based on

`RHEL 7.2`


<!-- Slide -->
### Kernel
3.10-based

<br>
### Hypervisor <!-- .element class="fragment" data-fragment-index="1"-->
KVM<!-- .element class="fragment" data-fragment-index="1"-->

ESX (vCenter)<!-- .element class="fragment" data-fragment-index="1"-->

Docker (OpenShift)<!-- .element class="fragment" data-fragment-index="1"-->
Note: Kernel API/ABI compatibility


<!-- Slide -->
Deployment

## OSP director
TripleO and Ansible

or

### Packstack


<!-- Slide -->
### Openstack Support

All Core Services plus

<table>
<tr>
    <td><img src="images/openstack/barbican-techpreview.svg"></td>
    <td><img src="images/openstack/ceilometer.svg"></td>
    <td><img src="images/openstack/designate-techpreview.svg"></td>
    <td><img src="images/openstack/fuel-notsupported.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/heat.svg"></td>
    <td><img src="images/openstack/horizon.svg"></td>
    <td><img src="images/openstack/ironic.svg"></td>
    <td><img src="images/openstack/magnum-notsupported.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/manila-techpreview.svg"></td>
    <td><img src="images/openstack/mistral-notsupported.svg"></td>
    <td><img src="images/openstack/murano-notsupported.svg"></td>
    <td><img src="images/openstack/sahara.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/tempest-notsupported.svg"></td>
    <td><img src="images/openstack/trove-techpreview.svg"></td>
    <td></td>
    <td><img src="images/openstack/legend.svg"></td>
</tr>
</table>


<!-- Slide -->
### Life Cycle 
New downstream version with 

###### every upstream release

Next: 

Newton, end of 2016, RHEL 7.3


<!-- Slide -->
Additionally recommended

### OSP director
### Satellite
### CloudForms


<!-- Slide -->
### Support
Two phases:
###### 1 year 
Full support (till August 2017)
###### 2 years
No feature backport, installer updates, new partner additions and certification (till August 2019)


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
###### Red Hat Ceph Storage 2.0

based on

### Jewel
RHEL 7.2 or Ubuntu 16.04

Note: v2.1 planed for Q4/2016


<!-- Slide -->
Deployment via
### Ansible
or
### RH Storage Console


<!-- Slide -->
###### CephFS

Tech preview in RHCS 2.0

Support planed for Q1/2017


<!-- Slide -->
## Pricing

Yearly subscriptions

based on:

raw capacity with node limit

Also available: <!-- .element class="fragment" data-fragment-index="1"-->

pre-production subscriptions <!-- .element class="fragment" data-fragment-index="1"-->

Note: 64TB subscription included in OSP

