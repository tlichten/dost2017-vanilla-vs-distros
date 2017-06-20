<!-- OpenStack -->
<!-- .slide: data-background-image="images/openstack-cloud-software-vertical-large.png" data-background-size="auto 90%" -->


<!-- Slide -->
Core Services: Higly `mature` and widely adopted.

<table>
<tr>
    <td><img src="images/openstack/swift.svg"    ></td>
    <td><img src="images/openstack/keystone.svg" ></td>
    <td><img src="images/openstack/nova.svg"     ></td>
</tr>
<tr>
    <td><img src="images/openstack/neutron.svg"  ></td>
    <td><img src="images/openstack/cinder.svg"   ></td>
    <td><img src="images/openstack/glance.svg"   ></td>
</tr>
</table>


<!-- Slide -->
Optional Services:

Lower level of `maturity` and `adoption`!

<table>
<tr>
    <td><img src="images/openstack/aodh.svg"></td>
    <td><img src="images/openstack/barbican.svg"></td>
    <td><img src="images/openstack/ceilometer.svg"></td>
    <td><img src="images/openstack/designate.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/fuel.svg"></td>
    <td><img src="images/openstack/heat.svg"></td>
    <td><img src="images/openstack/horizon.svg"></td>
    <td><img src="images/openstack/ironic.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/magnum.svg"></td>
    <td><img src="images/openstack/manila.svg"></td>
    <td><img src="images/openstack/mistral.svg"></td>
    <td><img src="images/openstack/monasca.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/murano.svg"></td>
    <td><img src="images/openstack/sahara.svg"></td>
    <td><img src="images/openstack/tempest.svg"></td>
    <td><img src="images/openstack/trove.svg"></td>
</tr>
</table>
Note: may add missing services Zaqar (Messaging Services), Congress (Governance)


<!-- Slide -->
What about Automation?

###### Write your own? <!-- .element class="fragment" data-fragment-index="1"-->

Sure! <!-- .element class="fragment" data-fragment-index="2"-->

<span class="fragment" data-fragment-index="3">
If you prefer the `epic fail`!
</span>


<!-- Slide -->
What does the 

### OpenStack Community?

`Ansible, Puppet, Chef`.


<!-- Slide -->
But what about 

`Fuel and Juju`?


<!-- Slide -->
May an option if you use

### Mirantis 
`Fuel`

or 

### Canonical
`Juju`

<span class="fragment"> `96%` of the code is from one `company` </span>


<!-- Slide -->
`But even then:`

The community code may not fit your needs. <!-- .element class="fragment" data-fragment-index="1"-->

It may takes quite some time to make it work. <!-- .element class="fragment" data-fragment-index="2"-->

You may stuck with a release longer than expected. <!-- .element class="fragment" data-fragment-index="3"-->

<br>
<span class="fragment" data-fragment-index="4"> `Very likely` means: <br> Lot of extra work for you! </span>
Note: e.g. upgrade or skip of releases


<!-- Ceph -->
<!-- .slide: data-background-image="images/ceph-logo.svg" data-background-size="auto 90%" -->


<!-- Slide -->
Most `mature`:

### RBD
block storage
### RadosGW
Swift/S3 oject store



<!-- Slide -->
Less mature:
###### CephFS


<!-- Slide -->
What about Automation?

<span class="fragment" data-fragment-index="1"> First: `Check above!` </span>

<br>
Then choose from <!-- .element class="fragment" data-fragment-index="2"-->

`ceph-deploy` <!-- .element class="fragment" data-fragment-index="2"-->

or <!-- .element class="fragment" data-fragment-index="2"-->

`Ansible, Puppet, Chef` <!-- .element class="fragment" data-fragment-index="2"-->


<!-- Slide -->
What are the 
## Alternatives 
### to Vanilla ?


<!-- Slide -->
Select a 
### Distribution

<img src="images/distros-all.svg" alt="Red Hat, SUSE, Mirantis, Canonical" style="width:90%;">


<!-- Slide -->
Leaves one question:

What is the 

### prefrered 

## Distribution

of your organization?

