## A report on Filecoin Bacalhau runtime performance
Summary:

Web 3.0's two major pillars are transparency and privacy. As a data monetization Dapp, we should construct our environment on these pillars, and decentralization makes it possible.
The confidentiality of data and the security of computing to data are crucial in our field of work.


Importance of compute to data: 
We are a data monetization Dapp, as we have just mentioned, and our clients are capable of running their data models on the provided data. 
We are a data monetization Dapp that collects and enriches raw data while preserving users' privacy and ownership.
Given that compute to data is one of the high-demand subjects in the field of data consumption, we want to provide an easy and secure space for our users to monetize their data without data being leaked, and for our clients to use the data insights without their data being abused in the process.
Within the Web 3.0 environment, our users should be able to see precisely what is happening with their data, and one of the best ways, if not the best way, to do so is using compute to data.
Bacalhau has established itself as one of the leading platforms in the computing to data industry, with many great features that can be very useful for various use cases; as a data monetization Dapp, we find these tools to be very useful and intriguing.
One of the things we're excited about is Bacalhau computing speed, which we assessed in the following case study.

Case study:
We mainly conducted a case study highlighting latency's significance when using Filecoin Bacalhau vs. Docker. 
We developed a docker image used in both scenarios to compare the execution times between running it through the Filecoin Bacalhau CLI and a docker execution. Given how the operating system affects the CPU's performance, we ran each test 100 times to eliminate any possible runtime inconsistency. 
A processing unit is considered N/N (=1), which N is determined by the execution time to simulate more complex computations. The time complexity of our test algorithm is O(2N) and the space complexity is O(N). As the execution time is the experiment’s primary variable, we defined the algorithm in a way that we can ignore the effect of space complexity on the results, as it’s only linear compared to the exponential time complexity.
In the experiment's first phase, we ran the docker for 235 or 34,359,738,368 operation units.
