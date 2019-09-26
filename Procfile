#web: rq-dashboard --port $PORT
web: PYTHONPATH=. RQ_DASHBOARD_PORT=$PORT python -c 'from rq_dashboard.cli import main; main()'
