---
layout: post
title:  "Race Car Katas - Telemetry"
categories: [SOLID Principles, Refactoring, Starter]
image: race_car_telemetry.png
---

## Credits

[Emily Bache](https://github.com/emilybache)

Handouts: [goo.gl/f7aGj9](https://goo.gl/f7aGj9)

## Get the code

[On Github](https://github.com/emilybache/Racing-Car-Katas)


## Your Task

Write the unit tests for the `TelemetryDiagnosticControls` class. The
responsibility of the `TelemetryDiagnosticControls` class is to
establish a connection to the telemetry server (through the
`TelemetryClient`), send a diagnostic request and successfully receive
the response that contains the diagnostic info. The `TelemetryClient`
class provided for the exercise fakes the behavior of the real
`TelemetryClient` class, and can respond with either the diagnostic
information or a random sequence. The real `TelemetryClient` class would
connect and communicate with the telemetry server via tcp/ip.