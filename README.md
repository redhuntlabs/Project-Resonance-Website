Hi there, 

You are visting this page most probably because you saw this url in your logs. Well, nothing to worry. 

### So, what Happened?
You recieved a innocent HTTP request from one of our distributed research engine as a part of **Project Resonance**. We perform internet-wide security research and send non-malicious and non-intrusive requests for the same.  We take special care of making sure no systems are negatively affected because of our scans.

### Alright, What is this Project Resonance?

Project Resonance is an effort to improve security of the Publicly Exposed Assets through study of the services and applications running on these assets followed by a deep analysis and data correlation.  

* We focus specifically on identifying different kinds of Systems and components which are unknown to System and Security teams. Examples of such systems/components are unknown custom headers, less popular services, custom protocols and their impact on security in general.

* Project Resonance covers not just Internet Wide Port Scanning but also goes deep into the studying and analysing other kinds of data on the internet. Such examples could be the patterns of Data Leakage on the Internet, study of security on cloud infrastructures, etc. 

* We plan to release one Wave at a time and in each Wave, we plan to cover one specific area of the internet and analyse the current security posture of the components in that area. Any interesting results will be shared with the community while making sure no confidential information about any organization is made accessible on the internet, after all we are doing this to facilitate internet wide security and research. 

### Did we access any of your Authenticated / Private resources?
No, we don't access any private / authenticated / protected resources.

### Exclusions

Project Resonance respects the will of owners to exclude their assets from our scans and that’s why the first thing we do is to exclude the hosts requested by individuals / organizations. 

The rest of the targets are then processed by our distributed scanning framework. We parse and save all the data based as it is retrieved. 

Once this process is done, our team carefully inspects if there is any sensitive information which shouldn’t be publicly released and finalizes which data should be made public. A lot of thought is put into this phase to ensure that the information we are exposing to the world can not be straight up weaponized.

### How to be excluded from our scans:

We take Exclusions very seriously and believe that it’s an important part of the process. 

All our HTTP requests will include the following User Agent string. In case you encounter such a string in your logs, that’s us. 
> Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_6) Project-Resonance (http://project-resonance.com/) (KHTML, like Gecko) Chrome/83.0.4103.61 Safari/537.36

And if you would not like any of our further probes, please drop us an email at exclusion@project-resonance.com

Please make sure that you include the list of IP Addresses / IP Ranges which you would like to get excluded. Once we hear from you, we will simply put your IP Ranges on our exclusion list and you will never see any probe from us. 

### Want to Read More?
You can read more about this project at [https://redhuntlabs.com/project-resonance](https://redhuntlabs.com/project-resonance). If you are interested to see what kind of datasets are released, please check out [https://redhuntlabs.com/project-resonance-datasets](https://redhuntlabs.com/project-resonance-datasets).

### Got some other questions?
We suggest you to have a loot at our FAQ section in Please feel free to drop any of your questions to our email address: info@project-resonance.com

Thanks for your time and patience.
