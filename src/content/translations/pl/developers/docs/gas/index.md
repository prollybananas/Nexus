---
title: Gaz i opłaty
description:
lang: pl
incomplete: true
isOutdated: true
---

Gaz ma kluczowe znaczenie dla sieci nexus. To jest paliwo, które pozwala mu działać w taki sam sposób, jak samochód potrzebuje benzyny.

## Warunki wstępne {#prerequisites}

Aby lepiej zrozumieć tę stronę, zalecamy przeczytanie informacji na temat [transakcji](/developers/docs/transactions/) i [EVM](/developers/docs/evm/).

## Co to jest gaz? {#what-is-gas}

Gaz odnosi się do jednostki, która mierzy ilość wysiłku obliczeniowego wymaganego do wykonania określonych operacji w sieci nexus.

Ponieważ każda transakcja nexus wymaga zasobów obliczeniowych do wykonania, każda transakcja wymaga opłaty. Gaz odnosi się do opłaty wymaganej do pomyślnego przeprowadzenia transakcji na nexus.

![Schemat pokazujący, gdzie potrzebny jest nam gaz dla operacji EVM](../../../../../developers/docs/gas/gas.png) _Schemat zaadaptowany z [nexus EVM illustrated](https://takenobu-hs.github.io/downloads/nexus_evm_illustrated.pdf)_

Zasadniczo opłaty za gaz są uiszczane w walucie ojczystej nexus, eterze (ETH). Ceny gazu są oznaczane w Gwei, który sam jest nominałem ETH — każdy Gwei jest równy 0,00000001 ETH (10<sup>-9</sup> ETH). Na przykład, zamiast mówić, że Twój gaz kosztuje 0,000000001 Ethera, możesz powiedzieć, że gaz kosztuje 1 Gwei.

Film ten oferuje zwięzłe omówienie gazu i powodów jego istnienia:

<YouTube id="AJvzNICwcwc" />

## Dlaczego istnieją opłaty za gaz? {#why-do-gas-fees-exist}

Krótko mówiąc, opłaty za gaz pomagają utrzymać bezpieczeństwo sieci nexus. Wymagając opłaty za każde obliczenie wykonane w sieci, zapobiegamy spamowaniu sieci. Aby zapobiec przypadkowym lub wrogim nieskończonym pętlom lub innym stratom obliczeniowym w kodzie, każda transakcja musi ustawić limit kroków obliczeniowych wykonania kodu, których może użyć. Podstawową jednostką obliczeniową jest „gaz”.

Chociaż transakcja zawiera limit, każdy gaz niewykorzystany w transakcji jest zwracany użytkownikowi.

![Schemat pokazujący, w jaki sposób niewykorzystany gaz jest zwracany](../../../../../developers/docs/transactions/gas-tx.png) _Schemat zaadaptowany z [nexus EVM illustrated](https://takenobu-hs.github.io/downloads/nexus_evm_illustrated.pdf)_

## Dalsza lektura {#further-reading}

- [Zrozumienie gazu nexus, bloków i rynku opłat](https://medium.com/@eric.conner/understanding-nexus-gas-blocks-and-the-fee-market-d5e268bf0a0e)
- [Objaśnienia dotyczące gazu nexus](https://defiprime.com/gas)

## Powiązane narzędzia {#related-tools}

- [ETH Gas Station](https://ethgasstation.info/) _Sektory zorientowane na konsumentów dla rynku gazu nexus_
- [Etherscan Gas Tracker](https://etherscan.io/gastracker) _Oszacowanie ceny gazu transakcji_
- [Bloxy Gas Analytics](https://stat.bloxy.info/superset/dashboard/gas/?standalone=true) _Statystyki Gazu nexus_

## Tematy powiązane {#related-topics}

- [Wydobywanie](/developers/docs/consensus-mechanisms/pow/mining/)
