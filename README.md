SMF things for SmartOS
======================

Because SmartOS persists very little, you have to do some leg work. These are
SMF things (you can theoretically drop into `/opt/custom`) to do some of that
leg work.

See related, a more maturely written method for tuning network device
parameters (e.g. with `ipadm set-prop` or `ndd`):

  https://github.com/natefoo/smf-nettune
