# Changelog

## Unreleased

Expose the `TransmitSlices`, `ReceiveSlices`, and related data types through the
public interface. Use these to control descriptor and data buffer allocations.

Change MTU reporting in DeviceCapabilities, skipping the FCS size if we're at
the frame limit.

## 0.1.0 - 2026-03-22

First release to crates.io. Supports

- imxrt-ral 0.6
- smoltcp 0.13

ENET\_1G is not supported.
