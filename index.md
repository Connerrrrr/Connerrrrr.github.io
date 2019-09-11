---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
[My Github Profile]({{site.data.settings.github}})  
My [Personal Github Page]({{site.data.settings.website}}) and [Github repository]({{site.data.settings.repository}})  
My Projects:  

* [Closed-Domain-Chatbot]({{site.data.settings.chatbot}})  
  * Has basic funtionality of giving out information based on user given queries and the features specifically for admin and normal users.
  * Being designed to be __closed-domain chatbot__ with __information-fetching system__.
  * Admins have the ability to view all the anonymous user feedbacks and capabilities to start cralwer, upload and check the documents held on __IBM Watson__.
  * Security of the communication between static frontend and backend is ensured by __JWT Oauth token__.
  * Logger is enable on backend as well to ensure backlog if something on backend fails in someway.
  * The crawler is now configured to be single-thread but has the option of multithread, other features can also be configured in config class, i.e. MAX_PAGES_FETCH for total amount of pages that the crawler will fetech and MAX_DEPTH_CRAWLING for crawling depth
* [nutrition-label-recognizer]({{site.data.settings.nutrition}})  
  * Worked as part of three-members-team to formulate a __Full-stack web app__ for detecting nutrition label based on uploaded images
  * __MongoDB__, __React__ and __Node.js (Express)__ following __RESTful API__.
  * Used __Google Optical Character Recognition__ (OCR) for detecting and displaying detailed information for each nutrition upon user clicking the name on the input nutrition label image.
  * Deployed on __Google Kubernetes Engine__, managed by __Istio__ with single external endpoint, __registered domain name__ with __HTTPS-only__ access.
  * Featured with generating and saving PDF report upon authenticated request.
* [Scrapy_douban]({{site.data.settings.scrapy}})
  * Initiated and implemented an individually designed web crawler, which crawls the rates and details from online movie rating website
  * Used python __Scrapy__ framework, __MySQL__, __XPath__
  * Utilized Matplotlib and Numpy libraries to visualize the data
