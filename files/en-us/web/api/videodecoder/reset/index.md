---
title: VideoDecoder.reset()
slug: Web/API/VideoDecoder/reset
page-type: web-api-instance-method
tags:
  - API
  - Method
  - Reference
  - reset
  - VideoDecoder
browser-compat: api.VideoDecoder.reset
---
{{securecontext_header}}{{DefaultAPISidebar("WebCodecs API")}}

The **`reset()`** method of the {{domxref("VideoDecoder")}} interface resets all states including configuration, control messages in the control message queue, and all pending callbacks.

## Syntax

```js
reset()
```

### Parameters

None.

### Return value

{{jsxref("Undefined")}}.

## Examples

The following example resets the `VideoDecoder`.

```js
VideoDecoder.reset();
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
