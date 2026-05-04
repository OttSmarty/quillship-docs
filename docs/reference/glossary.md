**Browse:** [README](../../README.md) · [Home](../index.md) · [Getting Started](../getting-started.md) · [API](../api-reference.md) · [Auth](../authentication.md) · [Webhooks](../webhooks.md) · [FAQ](../faq.md) · [Concepts](../concepts/content-model.md) · [GraphQL](../api/graphql.md) · [Rate Limits](../api/rate-limits.md) · [Python SDK](../sdks/python.md) · [JS SDK](../sdks/javascript.md) · [React Quickstart](../guides/quickstart-react.md) · [Migrate](../guides/migrate-from-wordpress.md) · [Deployment](../ops/deployment.md) · [CLI](../reference/cli.md) · [Glossary](../reference/glossary.md)

---

# Glossary

A list of terms used throughout the Quillship docs.

## Content

The digital assets, text, and media stored within Quillship. Content is organized into entries based on [Content Types](../concepts/content-model.md).

## Content Type

A reusable schema or template that defines the structure of an entry. It consists of various [Fields](../concepts/content-model.md) like text, media, or references.

## Field

A specific data point within a [Content Type](../concepts/content-model.md), such as a title, slug, or body text. Fields can have validation rules and are the building blocks of your content structure.

## Workspace

A top-level organizational container that houses your content, environments, and team members. Workspaces allow you to isolate different projects or clients within a single account.

## Environment

A specific version or instance of a [Workspace](#workspace), such as 'Development', 'Staging', or 'Production'. Environments allow you to test schema changes safely before deploying them to live users.

## Token

A secure string used to authenticate requests to the Quillship APIs. Tokens are managed in the dashboard and can be scoped to specific environments or permissions as described in [Authentication](../authentication.md).

## Webhook

An automated notification sent to a specified URL when events occur in Quillship, such as content publication or deletion. See the [Webhooks guide](../webhooks.md) for setup instructions.

## CMS

Content Management System. Quillship is a 'headless' CMS, meaning it manages the content layer and provides it via API, leaving the presentation layer to your own frontend applications.

## API

Application Programming Interface. Quillship provides REST and [GraphQL](../api/graphql.md) APIs to fetch, create, and manage your content programmatically.

## SDK

Software Development Kit. Quillship provides official libraries for [Python](../sdks/python.md) and [JavaScript](../sdks/javascript.md) to simplify integration with our APIs.

## REST

Representational State Transfer. A standard architectural style for web APIs that uses HTTP methods like GET and POST to interact with content. Details are in the [API Reference](../api-reference.md).

## GraphQL

A query language for APIs that allows clients to request exactly the data they need. Quillship's [GraphQL API](../api/graphql.md) provides a flexible alternative to REST.

## CDN

Content Delivery Network. A distributed network of servers that caches and serves your content from locations closest to your users to minimize latency.

## SSR

Server-Side Rendering. A technique where the HTML for a page is generated on the server for every request, often used with our [SDKs](../sdks/javascript.md) for SEO and performance.

## ISR

Incremental Static Regeneration. A hybrid approach that allows you to update static content after you've built your site, without needing to rebuild the entire site.

## SSE

Server-Sent Events. A standard allowing servers to push real-time updates to web pages over HTTP, used in Quillship for live content previews.

## HMAC

Hash-based Message Authentication Code. A mechanism used to verify the integrity and authenticity of [Webhooks](../webhooks.md) by signing the payload with a secret key.

## RT

Real-time.