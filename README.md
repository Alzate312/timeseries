# Machine Learning with TimeSeries and Sequence Data - AMLD 2018

This repo contains materials for the "Modeling timeseries and sequence data on AWS using Apache
MXNet and Gluon" workshop at [Applied ML Days](https://www.appliedmldays.org/) 2018. In this
workshop we learn how to model generic sequence data and timeseries data to do sequence prediction,
forecasting future timeseries, anomaly detection to name a few. We will use Apache MXNet a scalable
deep learning framework to train our neural networks. Once trained we will explore various scalable
deployment options on AWS for both real-time and batch inference.

## Slide
refer to slides for an introduction in to [time series modeling on
AWS](https://www.slideshare.net/mallyajiggs/time-series-modeling-workd-amld-2018-lausanne) 

## Agenda

0. [Introduction to ApacheMXNet and Gluon - Crash Course](intro_mxnet_gluon)
1. [Introduction to TimeSeries Analysis](intro_to_timeseries.ipynb)
2. [Univariate TimeSeries](univariate_timeseries_forecasting_lstm.ipynb)
3. [Multivariate TimeSeries Forecasting](multivariate_timeseries_forecasting.ipynb)
4. [TimeSeries Forecasting with DeepAR](sagemaker-timeseries)
5. [Seq2Seq with Apache MXNet](seq2seq)

## Prerequisites

- Setup an [AWS account](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-account.html)
- Option 1: Run on [Amazon
  SageMaker](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-setup-working-env.html)
- Option 2: Setup a notebook server on [AWS DL
  AMI](https://s3.amazonaws.com/smallya-test/strata-london/NotebookSetupAWS.html)

## Apache MXNet cheat sheet and Gluon  

- [MXNet Cheat Sheet](https://bit.ly/2xTIwuj)
- [Gluon Tutorial](https://github.com/zackchase/mxnet-the-straight-dope)
