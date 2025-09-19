# IBisPack

**IBisPack** is a collection of AFL scripts and tools designed to use **IBis** (BrokerIBis.exe) with [AmiBroker](https://www.amibroker.com/). IBis is a relay between TWS (Interactive Brokers desktop trading software) and users' trading software. IBis provides an easy way to access [Interactive Brokers TWS API](https://www.interactivebrokers.com/campus/ibkr-api-page/twsapi-doc/#api-introduction) through a **COM** API. It's intended to replace [IBController](https://gitlab.com/amibroker/ibcontroller) and extend its API to use all of TWS API (up to v1030 included).

---

## 🚀 Features

- Modular AFL functions for strategy development
- Predefined templates for indicators and signal generation
- Utility scripts for file handling, variable management, and logging
- Compatible with AmiBroker 6.3+ (6.93+ recommended)

---

## 📦 Contents

- `Scripts/` — library (IBis.afl) and sample scripts
- `Doc/` — documentation and usage
- `BrokerIBis.cfg` — configuration file
- `BrokerIBis.exe` — IBis program
- `BrokerIBis.reg` — .reg file to register BrokerIBis.exe as a COM server
- `INSTALL CONFIG USAGE` — you guess
- `TwsSocketClient.dll` — custom version of TWS Client library to handle edge cases (not mandatory)

---

## 🛠️ Requirements

- AmiBroker 6.3+ installed (Windows)
- Basic knowledge of AFL scripting
- Interactive Brokers account
- TWS installed

---

## 📚 Getting Started

1. Clone the repository:
```bash
   git clone https://github.com/your-username/IBisPack.git
```

2. Read "INSTALL CONFIG USAGE"

3. Experiment with sample scripts and understand code

---

## Contact

- Use github for technical/code issues only
- Contact *alligator* in [Amibroker forum](https://forum.amibroker.com/) for usage
or general questions
