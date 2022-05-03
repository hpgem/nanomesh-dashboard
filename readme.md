## Nanomesh dashboards

This repo contains dashboards for nanomesh. A dashboard is a web app to glance at and play with some data. They were developed using [Streamlit](https://streamlit.io/).

### Using nanomesh in your browser

| <img src="https://github.com/hpgem/nanomesh/raw/master/docs/_static/meshing_dash.png" alt="drawing" width="85%"/> | <img src="https://github.com/hpgem/nanomesh/raw/master/docs/_static/metrics_dash.png" alt="drawing" width="85%"/> |
| - | - |
| [Generate a 2D mesh](https://share.streamlit.io/hpgem/nanomesh-dashboard/master/meshing_dash.py) | [Calculate mesh metrics](https://share.streamlit.io/hpgem/nanomesh-dashboard/master/meshing_dash.py) |

### Running locally

First, install the requirements:

```console
pip install -r requirements.txt
```

To run:

- Generate a 2D mesh using this dashboard:
 
```console
streamlit run .\meshing_dash.py
```

- Compare mesh metrics using this dashboard:

```console
streamlit run .\metrics_dash.py
```
