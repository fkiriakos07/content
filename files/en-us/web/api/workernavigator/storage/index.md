---
title: "WorkerNavigator: storage property"
short-title: storage
slug: Web/API/WorkerNavigator/storage
page-type: web-api-instance-property
browser-compat: api.WorkerNavigator.storage
---

{{securecontext_header}}{{APIRef("Storage")}}{{AvailableInWorkers("worker")}}

The **`storage`** read-only property of the {{domxref("WorkerNavigator")}} interface
returns the singleton {{domxref("StorageManager")}} object used to
access the overall storage capabilities of the browser for the current site or app.
The returned object lets you examine and configure persistence of data stores and
learn approximately how much more space your browser has available for local storage
use.

## Value

A {{domxref("StorageManager")}} object you can use to maintain persistence for stored
data, as well as to determine roughly how much room there is for data to be stored.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{domxref("StorageManager")}}
- {{domxref("WorkerNavigator")}}
