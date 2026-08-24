# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

### Changed

- Do not return `Err` from `GovernorMiddleware` on extraction errors. This allows the error response to propagate to other middlewares.
