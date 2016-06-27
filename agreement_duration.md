## Duration of the agreement

This topic makes the start time and the end time of the agreement clear. Select one of the options below!

### Contractor will deliver Services for a number of days, months or years.

Contractor will provide the Services to Customer for {{period}}, unless the Agreement is cancelled under another provision of the Agreement.

`jurisdiction` US, UK

### {{party 1}} will provide the Services for as long as it takes to completes the Work Scope.

Contractor will provide the Services to {{party 2}} until Contractor completes the Work Scope.

### Contractor will provide the Services until the agreement is cancelled.

Contractor will provide the Services to Customer until the Agreement is cancelled.

`jurisdiction` Australia

### Agreement lasts for a short period but renews regularly.

The Agreement will bind the parties for {{period}}.  The Agreement will continue to automatically renew for the Term unless a party to the Agreement gives the other party {{period}} notice before the end of a Term.

`jurisdiction` EU

## Definitions

### Agreement
means [*]

### Services
means [*]

## Widgets

{
    "period": {
        "type": "choice",
        "guidance": "Do you want to measure the time limit in days, months or years? In the next step you can say how many days, months or years.",
        "text": [{
            "summary": "Time limit of days.",
            "val": "{{period number}} days"
        }, {
            "summary": "Time limit of months.",
            "val": "{{period number}} months"
        }, {
            "summary": "Time limit of years.",
            "val": "{{period number}} years"
        }]
    },

    "period number": {
        "type": "blank",
        "guidance": "Type in a number!",
        "text": "3"
    }
  }


