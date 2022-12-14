# Engine of Growth

The engine of growth I'm attempting to use is the sticky engine. Key metrics for this engine, according to [The Lean Startup][1], are:

- Churn rate
- Usage frequency
- Consumer rention rate
- Acquisition rate

```
churn = departures / starting_users
usage_frequency = total_usage / starting_users
acquisition_rate = arrivals / starting_users
growth = (1 - churn) * usage_frequency * acquisition_rate
```

## Acquisition Rate metric in Amplitude

Formula: `UNIQUES(B)/(UNIQUES(A) - UNIQUES(B))`

- A = Any Event
- B = New User

| Period  | New Users | Active Users | Acquisition Rate |
| ------- | --------- | ------------ | ---------------- |
| Overall | 194       | 234          | 4.85             |
| 2021-11 | 13        | 27           | 0.93             |
| 2021-12 | 11        | 30           | 0.58             |
| 2022-01 | 28        | 45           | 1.65             |
| 2022-02 | 15        | 37           | 0.68             |
| 2022-03 | 15        | 41           | 0.58             |
| 2022-04 | 16        | 41           | 0.64             |
| 2022-05 | 17        | 41           | 0.71             |
| 2022-06 | 9         | 34           | 0.36             |
| 2022-07 | 13        | 40           | 0.48             |
| 2022-08 | 15        | 44           | 0.52             |
| 2022-09 | 20        | 46           | 0.77             |
| 2022-10 | 21        | 56           | 0.6              |

This acquisition rate is based on the current month's active users. This won't be the whole story until I compare it with our churn rate.

## Questions

- How do users churn?
- What are our most effective acquisition channels?
- What's our churn rate?

[1]: https://www.amazon.com/Lean-Startup-Entrepreneurs-Continuous-Innovation/dp/0307887898
