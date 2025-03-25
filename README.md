# Disclaimer

To broaden collaboration and facilitate the adoption and expansion of customer solutions, PTC is sharing several field-developed IoT components. 

These artifacts are built using ThingWorx best practices, including the Building Block structure where appropriate, and are available to PTC Customers, Partners, and Customer Success for incorporation and enhancement as needed for specific use cases.

Please note, these components are not covered by PTC Technical Support and are not subject to any Technical Support Service Level Agreements (SLAs). 

However, PTC Customer Success teams and resources will, on a best-effort basis:

* Maintain and manage functionality across ThingWorx platform version releases.
* Actively address reported bugs.
* Continue to enhance functionality opportunistically and by request where possible.

ThingWorx subscription users can continue to log technical support tickets. ThingWorx Platform Technical Support will assist in isolating root causes and addressing platform-related product issues through standard ThingWorx platform maintenance. 

If the issue pertains to this specific component offered via PTC GitHub, PTC Support will direct inquiries to the appropriate internal PTC teams for further assistance.

These shared components are provided "as is," without any warranty, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.

All content is provided as "Releases" and is not directly in the Git Repo.  Cloning this Git Repo will not provide any content.

--------


# Thingworx Containerization Guide


This series of articles is tailored for professionals who are already familiar with **Kubernetes** and have experience deploying applications within a Kubernetes environment. If you have successfully utilized Kubernetes to manage and deploy applications and are looking to expand your expertise by integrating PTC's ThingWorx platform, this series is for you.



## How to get the package

Please go to the [release page](https://github.com/PTCInc/twx-k8s/releases) and download the latest package, the name pattern is: twx-k8s-vx.x.x.zip



## How to use it

Please unzip the package and you will see two folders: *project* and *book*



### HTML format guide

Please double click *book/html/index.html* file, you can view the guidance in html format.



### PDF format guide

Please open the pdf file under *book/typstpdf/pdf/* folder and you can see the pdf guidance.



All content is provided as "Releases" and is not directly in the Git Repo.  Cloning this Git Repo will not provide any content.



## Changelog

### [v0.1.3] - 2025-03-25
- Added "disclaimer" and license info to readme first, html/pdf content

### [v0.1.2] - 2025-03-25
- Changed the helm-chart from github.com/xudesheng/charts to github.com/PTCInc/thingworx-charts
- Fixed the resource section in emessage/main.yaml to align with new version of emessage chart


### [v0.1.1] - 2025-03-18
- Add README-first.pdf
- Intialized the publish process from internal gitlab to public github repo.





## License

### PTC Proprietary Freeware License

I accept the PTC End User License Agreement (https://www.ptc.com/en/documents/legal-agreements/on-premise-license-agreements) and agree that any software downloaded/utilized will be in compliance with that Agreement.  However, despite anything to the contrary in the License Agreement, I agree as follows:

I acknowledge that I am not entitled to support assistance with respect to the software, and PTC will have no obligation to maintain the software or provide bug fixes or security patches or new releases.

The software is provided “As Is” and with no warranty, indemnitees or guarantees whatsoever, and PTC will have no liability whatsoever with respect to the software, including with respect to any intellectual property infringement claims or security incidents or data loss.
