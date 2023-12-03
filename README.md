# Introduction to Belinda's Closet
Belinda’s Closet emerged in the fall of 2022 to address the growing need among students for suitable attire on their graduation day. In direct response to this need, the EDIC team (Equity, Diversity, Inclusion, and Community) at North Seattle College founded and established this crucial resource. The primary goal is to offer essential support to students within the broader Seattle Colleges system, ensuring they have access to professional clothing for interviews, employment, and graduation ceremonies. Emphasizing its not-for-profit nature, these clothing items come without financial burden to the student.

Currently situated within the Equity & Welcome Center at North Seattle College (NSC), Belinda’s Closet is easily shopable during designated [open hours](https://northseattle.edu/edic/belindas-closet), underscoring its commitment to accessibility. In fact, Belinda's has grown from a "closet" to a larger, need-based, retail-type space. Plans are in motion to extend this invaluable resource to every campus within the Seattle Colleges system.

In a notable development, the Bachelor of Applied Science-Application Development department at NSC embraced Belinda’s Closet as a client in June 2023. The overarching objective has been to develop comprehensive web and Android applications that cater to the digital aspirations of our client and enhance the range of services offered to students.

These frontend applications, complemented by a shared backend app supporting data and connected to cloud services, are strategically designed. Their primary focus is to empower staff to efficiently manage and update Belinda’s Closet inventory, maintaining the organization's commitment to serving the community. The user interface (UI) aims not only to showcase available items in the store but also to seamlessly connect with the backend, facilitating smooth processing of incoming and outgoing inventory through MongoDB.

Belinda's will begin offering additional services, as the development team continues to build out the tech to grow this vital service. 
 
## Table of Contents
- [About The Project](#about-the-project)
- [MVP Progress](#mvp-progress)
- [Wiki](#wiki)
- [Acknowledgements](#acknowledgements)
- [License](#license)
 
## About The Project
- Belinda's [web-based](https://github.com/SeattleColleges/belindas-closet-nextjs) frontend utilizes Typescript via `NextJs`.
 
	[![2.png](https://i.postimg.cc/mkYCxq3h/2.png)](https://postimg.cc/SYKJCgvp)

- The [android-based](https://github.com/SeattleColleges/belindas-closet-android) frontend was developed using `Koitlin` within `Android Studio`.

	[![2.png](https://i.postimg.cc/yNMRJ9h4/2.png)](https://postimg.cc/94B0KDNJ)

- `NestJs` was selected for [backend](https://nestjs.com/) services also using Typescript. 

- `Google Cloud` powers our storage and `MongoDB` hosts our database.

### Software & Tools Used
- [Next.js](https://nextjs.org/): for the web application
- [Android Studio](https://developer.android.com/studio?gclid=Cj0KCQiAmNeqBhD4ARIsADsYfTekXQtjhqJ8cl8GBV4Lmza-3twj7fpJ6BC73tf5vPeYJYChgA9M3JAaAlGTEALw_wcB&gclsrc=aw.ds): for the android application
- [Nest.js](https://nestjs.com/): for the server-side backend application
- [Postman](https://www.postman.com/): for testing API endpoints
- [MongoDB](https://www.mongodb.com/): for collecting data
- [JWT](https://jwt.io/): for authenticating users
- [Google Cloud](https://cloud.google.com/gcp?utm_source=google&utm_medium=cpc&utm_campaign=na-US-all-en-dr-bkws-all-all-trial-e-dr-1605212&utm_content=text-ad-none-any-DEV_c-CRE_665735450627-ADGP_Hybrid+%7C+BKWS+-+EXA+%7C+Txt_Google+Cloud-KWID_43700077223807304-kwd-6458750523&utm_term=KW_google%20cloud-ST_google+cloud&gad_source=1&gclid=Cj0KCQiAgqGrBhDtARIsAM5s0_lZss9iNTytw2uZ_WJ8_H0PGVmFvXwkK06n99z0LeosNebnEEVAkI4aAoWCEALw_wcB&gclsrc=aw.ds): for storage and eventually deploymnent
- Hosting: for availing these apps to the masses... TBD
 
## MVP Progress
As a student team primarily operating asynchronously, our journey commenced in late June '23, working diligently under a grant-approved program at NSC for the initial 100 days. Throughout the summer, we not only made significant strides in our project but also forged strong team bonds, marking our first collaborative experience. Collectively, we reached the milestone of MVP1 by November 3, 2023 within the mobile app.
- The following video links demonstrate our progress along the way:
	- Pre MVP1
		- [Web](https://youtu.be/3F6EpmJhGb8) 
		- [Mobile](https://www.youtube.com/shorts/M5jzwP3tuek)
	- MVP1
		- Web (The work on this application will continue April of 2024.)
		- [Mobile](https://www.youtube.com/watch?v=zAuxXCaYSyw)
	- Pre MVP2
		- Web (The work on this application will continue April of 2024.)
		- Mobile (Coming soon!)
	- MVP2
		- Web (Coming soon!)
   		- Mobile (Coming soon!)
 
## Wiki
- Though the belindas-closet repository serves as our "main" repo for this client, visit our other Wikis for more information on topics that include:
  - [mobile app](https://github.com/SeattleColleges/belindas-closet-android/wiki)
  - [web app](https://github.com/SeattleColleges/belindas-closet-nextjs/wiki)
  - [backend app](https://github.com/SeattleColleges/belindas-closet-nestjs/wiki)
 
## Acknowledgements
- Thanks to our professor BC Ko for his leadership, knowledge, and patience.
- Thanks to Belinda at Belinda's Closet and the NSC EDIC team for your endless passion in serving students.
- Thanks to [Miro](https://miro.com/app/dashboard/), [Smartsheet](https://www.smartsheet.com/welcome-customers-home), and [Notion](https://www.notion.so/product?utm_source=google&utm_campaign=2075789710&utm_medium=80211061601&utm_content=500427479647&utm_term=notion&targetid=kwd-312974742&gad_source=1&gclid=Cj0KCQiAgqGrBhDtARIsAM5s0_kCuNK8I-F-4u_Mj1ClGopPfB_VlD-Ris4aRIu9ospGViBIqqjhXqYaAgWpEALw_wcB) for student licensing of your product. 
 
## License
Copyright (c) 2023 North Seattle College Application Development Department

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
