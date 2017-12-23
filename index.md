---
layout: page
title: Ivan's innovation lab
subtitle: Architecture, culture and process
---

The intention of this lab is to build information system of fictitious company. We are going to use different architectural and design patterns, organizational structures and delivery process to support this.

You will learn how we:

- made decisions to use one pattern against the other,
- changed architecture, organization (culture) and process over time to respond to new requirements,
- made a foundation for successful digitalization.

The ultimate goal is to deliver better software faster. Today, that invariably means continuous delivery – for an installed product – or continuous deployment for an -aaS product.

![Success triangle](https://github.com/ivans-innovation-lab/ivans-innovation-lab.github.io/raw/master/img/successtriangle.png)

The architecture enables teams to be agile and autonomous. Together, the team of teams and the architecture enable continuous delivery/deployment. 

### Technology

- Java 8
- Spring (spring boot, spring cloud, spring data, spring data rest)
- Axonframework (eventsourcing, CQRS)
- Angular 4+ (atomic design)
- CircleCI (Continuous Integration)
- Atomist (ChatOps)
- H2, MySQL (event store, materialized views)
- RabbitMQ (event bus in micorservices architecture)

[Read more](https://www.gitbook.com/read/book/ivans-innovation-lab/my-company) and [join our Slack team](https://communityinviter.com/apps/idugalic/idugalic)


<div id="CommunityInviter"></div>
<script>
  window.CommunityInviterAsyncInit = function () {
    CommunityInviter.init({
      app_url:'idugalic',
      team_id:'idugalic'
   })
  };

  (function(d, s, id){
    var js, fjs = d.getElementsByTagName(s)[0];
    if (d.getElementById(id)) {return;}
    js = d.createElement(s); js.id = id;
    js.src = "https://communityinviter.com/js/communityinviter.js";
    fjs.parentNode.insertBefore(js, fjs);
  }(document, 'script', 'Community_Inviter'));
</script>
