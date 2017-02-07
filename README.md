# 2017-02 Raleigh Puppet User Group notes
## RPUG meeting news
+ [March 6 meeting with guest Trevor Vaughan on SIMP and Puppet](https://www.meetup.com/Raleigh-Puppet-User-Group/events/237050632/)
  -  We'll have a guest presenter, Trevor Vaughan of Onyx Point, Inc., and he will be giving an overview of System Integrity Management Platform (SIMP) and then do Q&A around Puppet items in general.

## Puppet ecosystem announcements and news bits
+ [Puppet 3 went EOL Jan 1, 2017](https://groups.google.com/forum/#!topic/puppet-announce/tSe_4KTS7t0) see also the [Puppet Enterprise Support Lifecycle](https://puppet.com/misc/puppet-enterprise-lifecycle):
  - Purely my opinion, but I think the PE support lifecycle is a bit aggressive: all PE releases up to PE 2016.4  will go EOL on April 30, 2017. At least PE 2016.4 is a Long Term Support version.
+ [Puppet Enterprise 2016.5 introduces high availability](https://groups.google.com/d/msg/puppet-announce/JpqXSO1p1Zw/htB9NJxLBQAJ)
+ [puppet-agent 1.9.0 released which includes Puppet 4.9.0.](https://groups.google.com/d/msg/puppet-announce/A0PrJJNylz4/XgL6mH7rDAAJ)
  - *Hiera 5 - a successor of the experimental Puppet lookup feature - is built into Puppet 4.9. Fixes for several bugs related to Unicode and UTF-8 support in Puppet." New top level fact: `cloud`."*
  - [However there are problems with Puppet 4.9.0; 4.9.2 to be released soon](https://groups.google.com/d/msg/puppet-users/H9xRUjkl2ZI/WdJ_NpwfDgAJ)
+ [Foreman 1.14.x line has been released.](https://theforeman.org/manuals/1.14/index.html#Releasenotesfor1.14)
+ [5 unknown Gems Foreman gems - Ohad Levy - Cfgmgmtcamp 2017](http://redhat.slides.com/olevy/foreman-hidden-gems-cfgmgmtcamp2017?token=EpFZb7yH#/)
+ Vox Pupuli blog posts
  - [12/22/2016 - Announced the deprecation of Puppet 3 in Vox Pupuli modules](https://voxpupuli.org/blog/2016/12/22/putting-down-puppet-3/)
  - [01/11/2017 - List few steps to be done before a Puppet-4-only release of a Vox Pupuli Module](https://voxpupuli.org/blog/2017/01/11/migrating-to-puppet4/)
+ [Puppet.com blog - Now updated for Puppet 4: the Puppet Language Style Guide - published on January 26, 2017](https://puppet.com/blog/now-updated-puppet-4-puppet-language-style-guide)
  - *"We are very excited to announce the release of the Puppet 4 style guide! This update to the Puppet Language Style Guide was a long-term cooperative effort between Puppet developers, writers, and of course, the Puppet community. Our deepest thanks go to the community for their invaluable contributions to this revision."*
+ [Get 10% off Puppet Training](https://groups.google.com/forum/#!topic/puppet-announce/N64SQa6JInI)
+ [puppetlabs-certregen 0.1.1 available](https://github.com/puppetlabs/puppetlabs-certregen)
  - *"The certregen module provides an easy way to regenerate and distribute expiring CA certificates with zero downtime. When you regenerate your CA certificate with the certregen module your existing CA key pair is reused. The regenerated CA certificate is effectively equivalent to the expiring CA certificate and preserves the validity of your existing certificates, so you can update and distribute your new CA certificate with no downtime."*
+ [PuppetModule.info](http://www.puppetmodule.info/)
  - *"a new site that publishes documentation for every module on Puppet Forge and GitHub - aka "Puppet Strings as a Service". "*


## Other SysAdmin/DevOps/Tech news
+ [Take the 2017 State of DevOps survey](https://devops-survey.com/index.php)
  - *"This year, we’ll be taking a scientific look at how technical practices, processes and culture affect everything from IT performance to employee retention, and how quickly an organization can learn and improve. We’ve partnered with DevOps Research & Assessment (DORA) as we have over the past few years, so you can expect the collective curiosity and wisdom of Gene Kim, Jez Humble, Nicole Forsgren and DevOps experts at Puppet."*
