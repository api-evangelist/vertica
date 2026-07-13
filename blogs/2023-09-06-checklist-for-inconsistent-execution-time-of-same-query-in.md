---
title: "Checklist for Inconsistent Execution Time of Same Query in Eon Mode"
url: "https://www.vertica.com/blog/checklist-for-inconsistent-execution-time-of-same-query-in-eon-mode/"
date: "2023-09-06"
author: "sruthi"
feed_url: "https://www.vertica.com/feed/"
---

In Eon Mode, when a query is executed and if the ROS containers associated to the tables in the query are not present in depot, it will fetch results from the communal storage bucket. In the next immediate run, the query should provide results to the user from the files present in the depot. However, there are scenarios where high count of queries against various tables run in parallel and depot i
