# Hermes

[![GoDoc](https://godoc.org/github.com/pantheonproject/hermes?status.svg)](https://godoc.org/github.com/pantheonproject/hermes)
[![Build Status](https://travis-ci.org/disintegration/imaging.svg?branch=master)](https://travis-ci.org/pantheonproject/hermes)
![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/pantheonproject/hermes.svg)
[![Coverage Status](https://coveralls.io/repos/github/pantheonproject/hermes/badge.svg?branch=master)](https://coveralls.io/github/pantheonproject/hermes?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/pantheonproject/hermes)](https://goreportcard.com/report/github.com/pantheonproject/hermes)
[![Maintainability](https://api.codeclimate.com/v1/badges/587313e7f1c57680e466/maintainability)](https://codeclimate.com/github/pantheonproject/hermes/maintainability)
[![GitHub](https://img.shields.io/github/license/pantheonproject/hermes.svg)](https://github.com/pantheonproject/hermes/blob/master/LICENSE)

A generic system for communicating with various message queue systems.

## Installation

`go get "github.com/pantheonproject/hermes"`

## Basic Usage

TODO: this

## Testing

On windows, the simplest way to test is to use the powershell script.

`./test.ps1`

To emulate the testing which occurs in build pipelines for linux and mac, run the following:

`go test ./... -race`
