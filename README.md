# CBT671
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 671 is from Ed Pancoast and contains a useful edit macro  *   FILE 671
//*           called ZOOM which allows you to retrieve a dataset    *   FILE 671
//*           by placing a cursor on its name.  ZOOM originally     *   FILE 671
//*           came from the TSO TIMES magazine from the Fall 1994   *   FILE 671
//*           issue.                                                *   FILE 671
//*                                                                 *   FILE 671
//*           email:  edward.pancoast@mail.va.gov                   *   FILE 671
//*                                                                 *   FILE 671
//*    DESCRIPTION:                                                 *   FILE 671
//*                                                                 *   FILE 671
//*             Contains one edit macro "ZOOM" and associated       *   FILE 671
//*             HELP file.  This edit macro was hand copied         *   FILE 671
//*             from an article in the Fall 1994 TSO Times.         *   FILE 671
//*                                                                 *   FILE 671
//*    PURPOSE: provide cursor sensitive DSN and DSNAME             *   FILE 671
//*             recognition allowing users to ZOOM into             *   FILE 671
//*             another dataset without leaving their current       *   FILE 671
//*             edit session.                                       *   FILE 671
//*                                                                 *   FILE 671
//*    USAGE:   place cursor anywhere within a valid DSN or         *   FILE 671
//*             DSNAME character and start ZOOM from the            *   FILE 671
//*             command line or a pre-defined PFKey.  PFKey         *   FILE 671
//*             use is recommended to minimize cursor               *   FILE 671
//*             repositioning.  If the cursor is left on the        *   FILE 671
//*             line, the first data line displayed will be         *   FILE 671
//*             searched for a valid dsn.                           *   FILE 671
//*                                                                 *   FILE 671
//*    FEATURES: - DSN syntax checking with SYSDSN                  *   FILE 671
//*              - Symbolic variable substitution                   *   FILE 671
//*              - concatenation recognition with member            *   FILE 671
//*                search option                                    *   FILE 671
//*              - automatic switch to browse mode if edit          *   FILE 671
//*                fails                                            *   FILE 671
//*              - allows edit sessions to be stacked               *   FILE 671
//*              - allows modular addition of new functions         *   FILE 671
//*                                                                 *   FILE 671
//*    INSTALL: Install by copying ZOOM to any concatenated         *   FILE 671
//*             SYSEXEC or SYSPROC library. Copy ZOOMP to a         *   FILE 671
//*             concatenated ISPPLIB library.                       *   FILE 671
//*                                                                 *   FILE 671
//*             For best results assign value "ZOOM" to a PF        *   FILE 671
//*             Key.                                                *   FILE 671
//*                                                                 *   FILE 671
```
