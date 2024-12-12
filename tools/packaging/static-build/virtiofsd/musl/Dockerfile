# Copyright (c) 2022 Intel
#
# SPDX-License-Identifier: Apache-2.0

FROM alpine:3.21.0

SHELL ["/bin/ash", "-o", "pipefail", "-c"]
RUN apk --no-cache add \
        bash \
        curl \
        gcc \
        git \
        libcap-ng-static \
        libseccomp-static \
        musl-dev && \
    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y
