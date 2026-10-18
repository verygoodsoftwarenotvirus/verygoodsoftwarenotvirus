### hi, I'm Jeffrey

Staff software engineer in Austin, TX. I mostly write Go, and mostly build small, specific
things that make my own life a little more convenient.

I have a [blog](https://blog.verygoodsoftwarenotvirus.dev) that I write, you can view the source for all of its content in [its repo](https://github.com/verygoodsoftwarenotvirus/blog).

### where the work is

I mostly build utilities for myself that improve my own life:

- [**prez**](https://github.com/verygoodsoftwarenotvirus/prez): a TUI that helps you manage your review queue. 
  It makes **PR**s **EZ**.
- [**hevy-cli**](https://github.com/verygoodsoftwarenotvirus/hevy-cli): a CLI for the workout
  tracker [Hevy](https://www.hevyapp.com) that builds my routines 4 weeks at a time.
- [**crono**](https://github.com/verygoodsoftwarenotvirus/cronometer): a CLI for pulling your
  food tracking data out of [Cronometer](https://cronometer.com), which has no official API.

All the work I'm "proud" of is held in [**Prim and Proper**](https://github.com/primandproper):

- [**primitives-go**](https://github.com/primandproper/primitives-go): what every service is
  built from and no service is. Providers, transports, and database tooling.
- [**platform-go**](https://github.com/primandproper/platform-go): a Go library (built on primitives-go) of the things a
  product has (identity, billing, audit, webhooks, and the rest), each shipping a store, its DDL,
  a mock, and a transport.

I have reference apps built with the above two libraries in order to flesh out the interfaces and specifications. They are:

- [**Dinner Done Better**](https://github.com/primandproper/dinnerdonebetter): meal planning for
  groups, with ranked-choice voting on what's for dinner and grocery lists that write themselves.
- [**No Small Parts**](https://github.com/primandproper/nosmallparts): real-time collaborative
  theater, where you write scripts and perform them in sync with friends, in the browser.
- [**Fijo**](https://github.com/primandproper/fijo): scheduling for one- and two-person
  businesses built on recurring appointments, with makeups, and cancellations.

And some miscellaneous stuff:

- [**tarpaulin**](https://github.com/primandproper/tarpaulin): finds Go functions with no direct
  unit test, which is something `go test -cover` can't tell you.

