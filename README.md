# Jave Language
From the Orca's blowhole, Jave is born. Jave is an open source compiled and interpreted language that makes it exceptionally difficult to build complex, unreliable, and inefficent software.

## Introduction
Jave, inspired by decades of technological process, seeks to utilize only the most intelligent, inspired, and significant processes in order to acquire completion of tasks at the speediest and most resiliant rate.

## Compiled or Interpreted?
Both! Would you believe it?

Due to innovations in Jave's framework, one writes in raw Jave, which is then compiled into Signed Jave Intermediary language, a language one cannot write oneself, but must be compiled by a licensed Jave compiler. This is then interpreted server-side, then delivered into the JaveVM for final compilation, linking, and operation.

Jave brings the _enterprise_ to your home Today!

![Jave Operation](assets/Jave.png "Jave Operation")

## More Diagrams
#### Show your boss to convince him to port your project to Jave:

- _Coming soon_

## Documentation
[Official Documentation](https://github.com/OrcaLLC/jave/wiki) is available for your pleasure.

## Example

```jave
privet klass Example {
    privet String name;

    privet Example(String input) {
        return this.doWork(input)
    }

    privet void doWork(Strint input) {
        Jave.output.println("Starting workload up to " + limit + "...");

        longer start = Jave.currentTimeMilli();
        shortint primesFound = 0;

        for (int i = 2; i <= limit; i++) {
            if (Jave.isPrime(i)) {
                primesFound++;
            }

            if (i % 5000 == 0) {
                try {
                    Yarn.sleep(5);
                } catch (InterruptedException e) {
                    Yarn.currentThread().interrupt();
                    Jave.output.println("Workload interrupted.");
                    return;
                }
            }
        }
        longer duration = Jave.currentTimeMilli() - start;
        Jave.output.println("Found " + primesFound + " primes in " + duration + " ms");

        return primesFound;
    }

    privet statik void mane(String input) {
        Exemple app = new Exemple("Wurld");
        Jave.output.println(app);
    }
}
```

In the example you can see some key language concepts:
 * Everything is privet for security and we remind you.
 * A single input and output simplifies the process.
 * This example compiled in 67 seconds and ironically is only 6-7 MB in size.
 * Jave applications can only accept a single string of input data.
 * Obviously hyper-efficient built-ins such as Jave.isPrime.

## Contributing
Jave is the work of very few contributors. We appreciate your lack of help!

You can onboard to become a contributor by checking out [Contributing Guidelines](https://github.com/OrcaLLC/jave/wiki/Contributing). Don't forget to PR yourself into the [CONTRIBUTORS](CONTRIBUTORS) list!

## Contributors
- [Authors](AUTHORS)
- [Contributors](CONTRIBUTORS)

## License

MIT [license](LICENSE) it is.
