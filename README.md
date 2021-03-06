# prosemirror-py

[![CircleCI](https://circleci.com/gh/fellowinsights/prosemirror-py.svg?style=shield)](https://circleci.com/gh/fellowinsights/prosemirror-py)
[![Code Coverage](https://codecov.io/gh/fellowinsights/prosemirror-py/branch/master/graph/badge.svg)](https://codecov.io/gh/fellowinsights/prosemirror-py)
[![Python Version](https://img.shields.io/pypi/pyversions/prosemirror-py.svg)](https://pypi.org/project/prosemirror-py/)
[![PyPI Package](https://img.shields.io/pypi/v/prosemirror-py.svg)](https://pypi.org/project/prosemirror-py/)
[![License](https://img.shields.io/pypi/l/prosemirror-py.svg)](https://github.com/fellowinsights/prosemirror-py/blob/master/LICENSE.md)

This package provides Python implementations of the following [ProseMirror](https://prosemirror.net/) packages:

-   [`prosemirror-model`](https://github.com/ProseMirror/prosemirror-model)
-   [`prosemirror-transform`](https://github.com/ProseMirror/prosemirror-transform)
-   [`prosemirror-test-builder`](https://github.com/ProseMirror/prosemirror-test-builder)
-   [`prosemirror-schema-basic`](https://github.com/ProseMirror/prosemirror-schema-basic)
-   [`prosemirror-schema-list`](https://github.com/ProseMirror/prosemirror-schema-list)

The original implementation has been followed as closely as possible during translation to simplify keeping this package up-to-date with any upstream changes.

## Why?

ProseMirror provides a powerful toolkit for building rich-text editors, but it's JavaScript-only. Until now, the only option for manipulating and working with ProseMirror documents from Python was to embed a JS runtime. With this translation, you can now define schemas, parse documents, and apply transforms directly via a native Python API.

## Status

The full ProseMirror test suite has been translated and passes. This project only supports Python 3. There are no type annotations at the moment, although the original has annotations available in doc comments.
