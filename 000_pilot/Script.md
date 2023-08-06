# Feather vs. Parquet: Which is the Best File Format for Your Data?

## Introduction

Hello everyone, and welcome to my YouTube channel! Today, we're going to dive into a fascinating topic for all data enthusiasts out there – the battle between Feather and Parquet file formats. In a previous Medium article by Raj.k, we explored their differences, but now, we'll take it a step further and see the results in action. I'll walk you through a script that converts a large CSV file to both Feather and Parquet formats, measuring their respective size reductions and read times. Let's find out which one comes out on top!

[Script Overview]

First, let's understand the purpose of this script. We want to compare the storage efficiency and read times of Feather and Parquet when converting a sizable 649Mb CSV file. The goal is to help you make an informed decision on which file format best suits your needs.

## Code for CSV to Feather Conversion

Here's the Python code used to convert the CSV file to Feather:

```python
[Place the Python code for converting CSV to Feather here]
```

### Result: Feather Conversion

After executing the script, we obtained the following result:

- A remarkable 73.41% reduction in file size.
- The time taken to read the Feather file was 1.51255 seconds.

[Code for CSV to Parquet Conversion]

Now, let's take a look at the Python code for converting the CSV file to Parquet:

```python
[Place the Python code for converting CSV to Parquet here]
```

### Result: Parquet Conversion

After running the Parquet conversion script, the results were as follows:

- An impressive 85.58% reduction in file size.
- The time taken to read the Parquet file was 2.18953 seconds.

## Analysis

Now that we have the numbers, it's time to interpret the results and decide which format is the winner. As we can see, both Feather and Parquet offer substantial size reductions compared to the original CSV file. However, the choice between the two depends on your specific needs.

If storage space is your primary concern and read time is less critical, then Parquet is the clear winner. It achieved an outstanding 85.58% reduction in file size, making it an excellent option for data storage.

On the other hand, if you value both storage efficiency and fast read times, Feather might be the better choice for you. It delivered a 73.41% reduction in size and outperformed Parquet with a 31% faster read time.

It's important to note that in this test, the difference in file size between Parquet and Feather was approximately 46%. So, if your data files are not excessively large, and you prioritize faster read times, Feather could be the more balanced option.

## Conclusion

In conclusion, both Feather and Parquet are powerful file formats, each with its own strengths. If you're looking to optimize storage space and don't mind slightly longer read times, Parquet could be the best fit for you. On the other hand, if you seek a more balanced solution with good storage reduction and faster reads, Feather might be your go-to format.

Remember, the right choice ultimately depends on your specific data requirements and preferences. Whichever format you choose, it's clear that CSV files are no longer the optimal option for storing your data efficiently.

I hope you found this video helpful in understanding the differences between Feather and Parquet. If you enjoyed it, please give it a thumbs up and consider subscribing to my channel for more exciting programming and data-related content. Feel free to leave your comments and questions below, and I'll be happy to engage in discussions with all of you. Thanks for watching, and I'll see you in the next video!