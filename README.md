<h2> Hi, I'm Kunal Sarpe! <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3dxMTNsN2lpeG1vcmlqYjNxM3FzNzk4b2N2YW5mejYyNmNxYnQyZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/S9RnJWRWoiRZlHgaHa/giphy.gif" width="50"></h2>
<p><em>Software Enginner at <a href="https://www.crisil.com/">Crisil</a><img src="https://github.com/user-attachments/assets/78046db8-3009-496f-bd99-a61dc81eff2b" width="30"></em></p>

[![Linkedin: kunal-sarpe]](https://www.linkedin.com/in/kunal-sarpe-bb6ba0341/)
[![GitHub kunalsrp5]](https://github.com/kunalsrp5)

```sql

WITH profile AS (
    SELECT
        'Kunal Sarpe'        AS name,
        'Data Engineer'      AS role,

        [
            'Python',
            'SQL'
        ]                    AS languages,

        [
            'Pentaho Data Integration',
            'Pentaho Report Designer',
            'Apache Spark',
            'Apache Airflow',
            'Snowflake',
            'Neon Postgres'
        ]                    AS tools,

        [
            'Batch Pipelines',
            'Incremental Loads',
            'DAG-Based Orchestration',
            'Analytics-Ready Modeling'
        ]                    AS architecture,

        [
            'Banking & Risk Analytics',
            'Regulatory Reporting',
            'Early Warning Signals'
        ]                    AS domains,

        {
            flagship_project : 'Earcandy – Music Streaming Analytics Platform',
            learning_focus   : 'Pandas, NumPy, Advanced SQL, pipeline design, system design, data structures and algorithms'
        }                    AS projects_and_learning,

        'Turning raw data into decision-ready insights'
                             AS mission
)

SELECT *
FROM profile;
```

