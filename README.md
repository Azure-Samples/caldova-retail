# Caldova Retail — Storefront (eShopLite.StoreFx)

A small ASP.NET MVC 5 storefront on .NET Framework 4.8, backed by Entity Framework 6 and SQL Server. It lists products and stores, handles sign-in, and keeps a cart. This is the customer-facing app in the Caldova Retail modernization scenario.

# 🔑 Demo logins

The lab applications ship with seeded accounts. Whenever a module tells you to sign in, these are the credentials.

## Caldova storefront

| Username | Password | Role | Notes |
| --- | --- | --- | --- |
| `alice` | `Password1!` | Admin, Manager | Has existing order history |
| `bob` | `Password1!` | Employee | Has existing order history |

Either account works for the sign-in and cart checks the labs ask you to run.

> ⚠️ These are throwaway credentials for a local sandbox, and the authentication behind them is deliberately insecure — salted SHA-1 password hashes. That is the "before" state the bootcamp migrates away from.