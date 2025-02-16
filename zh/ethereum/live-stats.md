---
title: Live Stats
description: Descriptions of live how live statistics are calculated on TxStreet.
published: true
date: 2021-03-18T22:49:32.433Z
tags: ethereum
editor: markdown
dateCreated: 2021-03-14T14:59:01.153Z
---

## Broadcasted Tx/Sec

Broadcasted transactions per second measures the number of new and unique transactions broadcasted within the last 5 minutes. This number is then divided by 300 to reach an average "per second" result. This number is then divided by 300 to reach an average "per second" result.

## Confirmed Tx/Sec

Confirmed transactions per second measures rate of confirmed transactions per second over the past hour. Confirmed transactions per second measures rate of confirmed transactions per second over the past hour. If there was no confirmed block in the past hour, the timespan is increased past one hour to the last block's timestamp.

## Mempool Count

Mempool Count measures the total number of "pending" and "queued" transactions in the mempool on the TxStreet Ethereum node.

## Median Contract Fee

Median Contract Fee measures the median fee (in USD) from new and unique transactions broadcasted within the last 5 minutes with a gasLimit greater than 21000. Median Contract Fee measures the median fee (in USD) from new and unique transactions broadcasted within the last 5 minutes with a gasLimit greater than 21000. Since Ethereum gas fees are not exact until after the transaction is confirmed, this gas is first divided by "Median Tx Gas Used/Limit" for transactions with a gasLimit greater than 42000. This is why this number is an estimate and not exact. This is why this number is an estimate and not exact.

## Median ETH Transfer Fee

Median ETH Transfer Fee measures the median fee (in USD) from new and unique transactions broadcasted within the last 5 minutes with a gasLimit equal to 21000.

## Median Gas Price

Median Gas Price measures the median gasPrice from new and unique transactions broadcasted within the last 5 minutes.

## Last Block

Last Block is the difference in time from now and the timestamp attached to the last block. The timestamp is generated by miners and is not exact, which is why the measurement may be higher than the truth. The timestamp is generated by miners and is not exact, which is why the measurement may be higher than the truth.

## Median Txs Per Block

Median Txs Per Block measures the median number of transactions included in each block over the last hour.

## Gas Limit

Block Gas Limit is the maximum amount of gas that a block is allowed to contain, using the sum of the gas used by all transactions in that block. The maximum gas limit is voted on by miners of the Ethereum Network. The maximum gas limit is voted on by miners of the Ethereum Network.

## Median Block Gas

Median Block Gas measures the median gas used by a block (sum of the gas used by all transactions in that block) over the last hour.

## Median Block Size

Median Block Size measures the median data used by a block (in megabytes) over the last hour.

## Median Tx Gas Used/Limit

Median transaction gas used/limit. Median transaction gas used/limit. First, the average (gasUsed / gas) of each transaction greater than 21000 gas in a recently mined block is obtained. This average is appended to a list of averages (no more than 500 in length), from which the final median result is reached. This average is appended to a list of averages (no more than 500 in length), from which the final median result is reached.

## Average Block Time

Average Block Time measures the average time between mined blocks over the last 250 blocks.