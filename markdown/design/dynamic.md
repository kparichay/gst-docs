# Dynamic pipelines

This document describes many use cases for dynamically constructing and
manipulating a running or paused pipeline and the features provided by
GStreamer.

When constructing dynamic pipelines it is important to understand the
following features of gstreamer:

  - pad blocking

  - playback segments.

  - streaming vs application threads.
