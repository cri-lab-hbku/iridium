This page is dedicated to the distribution of the data used for the paper: "GNSS Spoofing Detection via Opportunistic IRIDIUM Signals", by Gabriele Oligeri, Savio Sciancalepore, and Roberto Di Pietro, accepted at the 2020 ACM Conference on Security and Privacy in Wireless and Mobile Networks.

In our paper, these data have been used to detect ongoing GPS spoofing activities on a target moving device in a remote location, such as deserts or oceans.

The hardware used for data acquisition is mainly constituted bya Software Defined Radio USRP X310, a telescopicstiloantenna,and a Laptop Dell XPS15 9560, equipped with 32GB of RAM and8 Intel Core i7700HQ processors running at 2.80 GHz. As for thesoftware, we adopted the GNURadio development toolkit and therelated Iridium module [1]. The output is subsequently parsed togenerate meaningful data analytics.

Within each file, there are 8 columns, whose meaning is according to the following description:

col.1: unix timestamp at the beginning of the data acquisition
col.2: timestamp in ms, related to the reception of the message
col.3: satellite ID
col.4: beam ID (if 0, the reported position is related to the position of the satellite at ground)
col.5: latitude coordinate
col.6: longitude coordinate
col.7: altitude coordinate (if about 800, it is the satellite)
col.8: estimated accuracy of the decoded signal

For any question or further data, you can contact:

- Gabriele Oligeri, goligeri@hbku.edu.qa
- Savio Sciancalepore, ssciancalepore@hbku.edu.qa

Enjoy the data!