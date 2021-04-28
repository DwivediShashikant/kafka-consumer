# kafka-consumer

A Clojure utility that demonstates how a kafka producer produces a message to a certain topic.
This repo is a consumer and the messaged are pushed by [kafka-producer](https://github.com/DwivediShashikant/kafka-producer)

## Usage

poll for the messages pushed by [kafka-producer](https://github.com/DwivediShashikant/kafka-producer) for a certain topic by using the command:
```clojure
lein producer $Home\IdeaProjects\kafka-producer\config\kafka\java.config <top-name>
```
example: 
```clojure
lein producer $Home\IdeaProjects\kafka-producer\config\kafka\java.config test10
```

## License

Copyright © 2021 FIXME

This program and the accompanying materials are made available under the
terms of the Eclipse Public License 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

This Source Code may also be made available under the following Secondary
Licenses when the conditions for such availability set forth in the Eclipse
Public License, v. 2.0 are satisfied: GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or (at your
option) any later version, with the GNU Classpath Exception which is available
at https://www.gnu.org/software/classpath/license.html.
