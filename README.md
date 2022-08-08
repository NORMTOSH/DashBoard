# DashBoard
Just about any Python library can be used to create a “static” PNG, SVG, HTML, or other output that can be pasted into a presentation, sent in an email, published as a figure in a paper, and so on. Many people also want or need to create “live” Python-backed applications or dashboards that a user can interact with to explore or analyze some data. Python offers several libraries for this purpose. The four main tools designed specifically for web-based dashboarding in Python are:

* Dash (from Plotly); see the blog post

* Panel (from Anaconda); see the blog post

* Voila (from QuantStack); see the blog post; used with separate layout tools like jupyter-flex or templates like voila-vuetify.

* Streamlit; see the blog post

You can see comparisons of these tools in:

* Streamlit vs Dash vs Voilà vs Panel — Battle of The Python Dashboarding Giants 30 Mar 2021 Stephen Kilcommins. Comparing Streamlit, Dash, Voilà, and Panel for   dashboarding. Links to more detailed explorations for each library individually.

* Are Dashboards for Me? 7 Jul 2020 Dan Lester. Overview of Python and R dashboard tools, including Voila, ipywidgets, binder, Shiny, Dash, Streamlit, Bokeh, and Panel.

There are also other tools that can be used for some aspects of dashboarding as well as many other tasks:

* Bokeh is a plotting library, a widget and app library, and a server for both plots and dashboards. Panel is built on Bokeh, providing a higher-level toolkit specifically focused on app and dashboard creation and supporting multiple plotting libraries (not just Bokeh).

* ipywidgets provides a wide array of Jupyter-compatible widgets and an interface supported by many Python libraries, but sharing as a dashboard requires a separate deployable server like Voila.

* matplotlib supports many different backends, including several native GUI toolkit interfaces such as Qt that can be used for building arbitrarily complex native applications that can be used instead of a web-based dashboard like those above.

* Bowtie (from Jacques Kvam) allows users to build dashboards in pure Python.

* flask is a Python-backed web server that can be used to build arbitrary web sites, including those with Python plots that then function as flask dashboards, but is not specifically set up to make dashboarding easier.
