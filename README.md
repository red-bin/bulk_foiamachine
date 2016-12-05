# bulk_foiamachine

./submit_foia --help
Uses some silly screenscraping to submit a FOIA request.

Usage: 
  ./submit_foia --title=<s> --body=<s> --agency=<s> (--allstates|--jurisdiction=<s>)  [--force]

Options:
  -t, --title=<s>           Title of request
  -b, --body=<s>            Body of request
  -A, --allstates           Submit to all states.
  -j, --jurisdiction=<s>    Jurisdiction to send to.
  -a, --agency=<s>          Agency to send to.
  -f, --force               Send without asking.
