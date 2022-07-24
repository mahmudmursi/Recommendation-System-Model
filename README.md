# Recommendation-System-Model

About Dataset

Context

Deskdrop is an internal communications platform developed by CI&T, focused in companies using Google G Suite. Among other features, this platform allows companies employees to share relevant articles with their peers, and collaborate around them.

Content
This rich and rare dataset contains a real sample of 12 months logs (Mar. 2016 - Feb. 2017) from CI&T's Internal Communication platform (DeskDrop).
I contains about 73k logged users interactions on more than 3k public articles shared in the platform.

This dataset features some distinctive characteristics:

Item attributes: Articles' original URL, title, and content plain text are available in two languages (English and Portuguese).
Contextual information: Context of the users visits, like date/time, client (mobile native app / browser) and geolocation.
Logged users: All users are required to login in the platform, providing a long-term tracking of users preferences (not depending on cookies in devices).
Rich implicit feedback: Different interaction types were logged, making it possible to infer the user's level of interest in the articles (eg. comments > likes > views).
Multi-platform: Users interactions were tracked in different platforms (web browsers and mobile native apps)
If you like it, please upvote!

Take a look in these featured Python kernels:

Deskdrop datasets EDA: Exploratory analysis of the articles and interactions in the dataset
DeskDrop Articles Topic Modeling: A statistical analysis of the main articles topics using LDA
Recommender Systems in Python 101: A practical introduction of the main Recommender Systems approaches: Popularity model, Collaborative Filtering, Content-Based Filtering and Hybrid Filtering.
Acknowledgements
We thank CI&T for the support and permission to share a sample of real usage data from its internal communication platform: Deskdrop.

Inspiration
The two main approaches for Recommender Systems are Collaborative Filtering and Content-Based Filtering.

In the RecSys community, there are some popular datasets available with users ratings on items (explicit feedback), like MovieLens and Netflix Prize, which are useful for Collaborative Filtering techniques.

Therefore, it is very difficult to find open datasets with additional item attributes, which would allow the application of Content-Based filtering techniques or Hybrid approaches, specially in the domain of ephemeral textual items (eg. articles and news).

News datasets are also reported in academic literature as very sparse, in the sense that, as users are usually not required to log in in news portals, IDs are based on device cookies, making it hard to track the users page visits in different portals, browsing sessions and devices.

This difficult scenario for research and experiments on Content Recommender Systems was the main motivation for the sharing of this dataset.
