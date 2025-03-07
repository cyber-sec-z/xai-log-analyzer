| Feature Name            | Description |
|-------------------------|-------------|
| total_requests          | Total number of requests made by the IP. |
| get_ratio               | Ratio of GET requests to total requests. |
| get_to_other_ratio      | Ratio of GET requests to other HTTP methods. |
| mean_rps                | Average requests per second (RPS) for the IP. |
| inter_request_skew      | Skewness in the time intervals between consecutive requests, indicating bursty or uniform request patterns. |
| burstiness              | Measures irregular spikes in request activity, helping detect aggressive scanning or attacks. |
| method_diversity        | Number of unique HTTP methods used (GET, POST, PUT, etc.), indicating request variation. |
| status_code_diversity   | Count of unique HTTP status codes returned (e.g., 200, 404, 500), useful for detecting unusual response patterns. |
| failure_success_ratio   | Ratio of failed requests (4xx, 5xx) to successful ones (2xx), indicating potential probing behavior. |
| success_ratio           | Proportion of successful (2xx) responses relative to total requests. |
| duplicate_url_ratio     | Fraction of repeated URLs in the request set, which may indicate automated behavior. |
| avg_malicious_prob      | Average probability of requests being malicious, as assigned by the first-tier model. |
| avg_benign_prob         | Average probability of requests being benign, as assigned by the first-tier model. |
| frequency_var           | Variability in request frequency over time, detecting inconsistent or periodic request patterns. |
| unique_user_agents      | Number of distinct user agents used by the IP, indicating potential spoofing or bot-like behavior. |
