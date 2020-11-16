
![EAS model](/visum-EAS model.png)

capability
> |Name|Description|
> |-----|----------|
> |_id| |
> |description| |
> |levelOne|Top level of classification of Buiness Capabilities. |
> |levelTwo|Sub Group of Buiness Capabilities |
> |lob|Line of Business |
> |name| |


tech
> |Name|Description|
> |-----|----------|
> |_id| |
> |cost| |
> |costPer|Seat, Month, Year, One Time |
> |description| |
> |lifecycle|Planning,Phase In, Active, Phase Out |
> |name| |
> |subType|Group of simular Tech |
> |type|What is the tech grouping? I.E. Database, COTS... |
> |version|What version of the tech is this. |


provider
> |Name|Description|
> |-----|----------|
> |_id| |
> |cost| |
> |costPer|Seat, Month, Year, One Time |
> |description| |
> |location| |
> |name|Name of the provider. On Prem, AWS, Azure, Google |


component
> |Name|Description|
> |-----|----------|
> |_id| |
> |dependants|List of compoent that this component depends on |
> |description| |
> |lifecycle|Planning,Phase In, Active, Phase Out |
> |name| |
> |platform|What cloud platform or vnc is this deploy too|
> |provider|link to the provider of this component |
> |techstacks|List of techstacks this component uses|
> |type|Web, BFF, atomic, composite, data stream,Event Dispatcher, event consumer, database| l



application
> |Name|Description|
> |-----|----------|
> |_id| |
> |businessCritcality|How important is this application to the over all success of the business, adminstrative service, business operational, business critical, and mission critical |
> |capabilities|What capability does this application address |
> |components|List of components in this application |
> |description| |
> |functionalFit|How well does this application do the job. Unreasonable, insufficient, appropriate, and perfect |
> |lifecycle|Planning,Phase In, Active, Phase Out |
> |name| |
> |predecessor|What application was before this one. |
> |successor|What application replaces this one.|
