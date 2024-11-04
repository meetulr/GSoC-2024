
# GSoC-2024

## About Project
**Dashboard**: *[Tag Management System | Google Summer of Code](https://summerofcode.withgoogle.com/programs/2024/projects/9GWfCSa3)* <br />
**Mentors**: *[@rishav-jha-mech (Rishav Jha)](https://github.com/rishav-jha-mech), [@beingnoble03 (Noble Mittal)](https://github.com/beingnoble03), [@Nitya-Pasrija (Nitya Pasrija)](https://github.com/Nitya-Pasrija)* <br />
**Repositories**: *[talawa-admin](https://github.com/PalisadoesFoundation/talawa-admin/tree/develop), [talawa-api](https://github.com/PalisadoesFoundation/talawa-api/tree/develop)* <br />
**Organization**: *[The Palisadoes Foundation](https://www.palisadoes.org) - [Github](https://github.com/PalisadoesFoundation)*

---

## Project Summary


This project introduces a `userTag` management system into Talawa’s community management platform, significantly enhancing administrators' ability to oversee and interact with community members. As a core addition to the admin portal, this feature enables streamlined management of tags through a comprehensive set of CRUD (Create, Read, Update, Delete) operations, allowing administrators to create specific tags for classifying community members and activities.

Beyond basic CRUD functionalities, the `userTag` feature includes sophisticated tools for managing tag-related activities and operations. With this suite of capabilities, administrators can perform bulk actions, like assignment/removal of tags, and monitoring of tags and tag related activities. which will be beneficial for creating workflows around tag-based member groups, making it easier to target specific subsets of users. By efficiently handling these tagging operations, administrators can establish a more organized structure within their communities, tailored to unique interactions and specific engagement needs. This level of granularity in user management enables better tracking of user activities and trends within the platform, while also providing support for meaningful and targeted community engagement strategies.

Ultimately, Talawa’s enhanced tag management system empowers administrators with a powerful and intuitive toolset for fostering active, well-organized, and engaged communities. By segmenting users and applying targeted engagement strategies, admins can optimize communication, promote relevant events or content, and drive stronger, more personal connections among community members. This new feature elevates the Talawa platform’s ability to support vibrant, organized community ecosystems with a focus on user-centric management and enhanced community insights.

---

## Code

### Talawa-admin:
1. Implement Tags UI:
	- **Issue**: *[link](https://github.com/PalisadoesFoundation/talawa-admin/issues/2037)*
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-admin/pull/2175)
2. Implement Manage Tags UI:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-admin/issues/2184)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-admin/pull/2185)
3. Implement SubTags UI:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-admin/issues/2195)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-admin/pull/2196)
4. Adding People To Tags:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-admin/issues/2302)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-admin/pull/2355)
5. Bulk Tag Operations:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-admin/issues/2357)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-admin/pull/2362)
6. Redesign and Refactor:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-admin/issues/2382)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-admin/pull/2387)
7. Filtering and Sorting:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-admin/issues/2395)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-admin/pull/2398)

### Talawa-api
1. Add UserTags connection:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-api/issues/2393)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-api/pull/2394)
2. New Resolvers and Backend Adjustments:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-api/issues/2459)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-api/pull/2460)
3. Add Support for Adding People to Tag:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-api/issues/2552)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-api/pull/2612)
4. Add Support for Bulk Tag Operations:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-api/issues/2614)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-api/pull/2616)
5. Add Support for Filtering and Sorting:
	- **Issue**: [link](https://github.com/PalisadoesFoundation/talawa-api/issues/2630)
	- **Pr**: [link](https://github.com/PalisadoesFoundation/talawa-api/pull/2635)

---

## Thoughts
Honestly, signing up for Google Summer of Code (GSoC) was a bit daunting. When I first got into open source, I was just hoping to get comfortable enough with code that I wouldn’t feel like an imposter every other day!

The Palisadoes Foundation ended up being the perfect starting point. It was my gateway into open source, and with the support of the amazing folks there, I finally took the plunge and applied for GSoC. Spoiler alert: I survived, and it was totally worth it. [Meet Meetul Rathore – The Palisadoes Foundation](https://www.palisadoes.org/news/2024/09/02/meet-meetul-rathore/)

Big thanks to all the talented and patient contributors who’ve made this journey both educational _and_ fun. I'm excited to keep contributing, keep learning, and keep meeting more awesome people in the open-source world.

To all my fellow contributors and mentors: you made this experience unforgettable (and way less intimidating). And to Google: thanks for creating such a wonderful program that teaches so much.

Here’s to facing our fears, learning, and growing together!
