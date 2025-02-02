---
layout: page
title: Vanilla OS Roadmap
description: The roadmap for the stable release of Vanilla OS.
---
## Terms

* **Stable**: A release that is ready for production use.
* **Closed/Open Beta**: A release that is ready for testing and feedback.
* **Release Candidate**: A release that is proposed for the stable release.

All releases are always available for download on our GitHub page, the main
difference is the level of support and stability.

## Timeline

Below are the timelines for each release of Vanilla OS, including testing 
versions. Those are not all the tasks, but rather the most important ones,
every release will have a lot of other tasks that are not listed here, like
bug fixes, translations, qol improvements, etc.

### 2.0 Orchid (testing)

<div class="timeline" id="timeline_2"></div>

<br />

### 22.10 Kinetic (stable)

<div class="timeline collapsed" id="timeline_2210"></div>

<br />

<script type="text/javascript" src="/assets/js/tableStatus.js"></script>
<script type="text/javascript" src="/assets/js/timeline.js"></script>

<script>
    generateTimeline(
        {
            events: [
                {
                    date: "26 February 2023",
                    title: "Freeze",
                    description: "The development of Vanilla OS 22.10 will be frozen until the next release.",
                    className: "timeline-green"
                },
                {
                    date: "26 February 2023",
                    title: "Manual Partitioning Support",
                    description: "Added Manual Partitoning Support to Installer",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "26 February 2023",
                    title: "Panels removed in Vanilla Control Center",
                    description: "Drivers and PRIME Profiles panels have been moved to Settings from Vanilla Control Center",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "February 2023",
                    title: "Nix Support",
                    description: "Added support for Nix packages in Apx",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "February 2023",
                    title: "Rollback Support",
                    description: "Added option to rollback to previous root partition in ABRoot",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "February 2023",
                    title: "VRR Session",
                    description: "Experimental VRR package with GNOME Session has been added",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "January 2023",
                    title: "Bug Fixes",
                    description: "Bugs reported by the community will be fixed.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "29 December 2022",
                    title: "Stable",
                    description: "The first stable release of Vanilla OS.",
                    className: "timeline-dimmed-green"
                },
                {
                    title: "Release Candidate builds are available for testing.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "28 November 2022",
                    title: "ABRoot Ready",
                    description: "ABRoot is ready to be included in the next release.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "11 November 2022",
                    title: "Slowdown #1",
                    description: "We have decided to <a href='/2023/01/28/almost-vs-abroot.html'>deprecate Almost for ABRoot</a>, a new utility designed to provide a more robust and full atomic immutability model, as a result the next release will be delayed by a few weeks.",
                    className: "timeline-red"
                },
                {
                    date: "24 October 2022",
                    title: "Open Beta",
                    description: "The first open beta of Vanilla OS.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "09 October 2022",
                    title: "Closed Beta 2",
                    description: "The second Closed Beta stage of Vanilla OS begins.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "01 October 2022",
                    title: "Closed Beta 1",
                    description: "The first Closed Beta stage of Vanilla OS begins.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "24 September 2022",
                    title: "Alpha",
                    description: "First Alpha release of Vanilla OS.",
                    className: "timeline-dimmed-green"
                }
            ]
        },
        "#timeline_2210"
    );

    generateTimeline(
        {
            events: [
                {
                    date: "No date yet",
                    title: "GNOME 44",
                    description: "Vanilla OS 2.0 will be based on GNOME 44 (not guaranteed).",
                    className: "timeline-grayed"
                },
                {
                    date: "No date yet",
                    title: "Waydroid support in Apx",
                    description: "We are working on adding <a href='https://github.com/Vanilla-OS/apx/issues/118'>Android support to Apx</a>.",
                    className: "timeline-grayed"
                },
                {
                    date: "Working on",
                    title: "desktop-image",
                    description: "We are working to the desktop image of Vanilla OS. This is the official image of Vanilla OS.",
                    className: "timeline-green"
                },
                {
                    date: "Working on",
                    title: "core-image",
                    description: "We are working to the core image of Vanilla OS. This image will be used as a base for the desktop image and flavors.",
                    className: "timeline-green"
                },
                {
                    date: "Working on",
                    title: "pico-image",
                    description: "We are working to the pico image of Vanilla OS. This image will be used as a base for the core image and live iso.",
                    className: "timeline-green"
                },
                {
                    date: "Working on",
                    title: "Vib",
                    description: "We are working on a new OCI image builder for Vanilla OS.",
                    className: "timeline-green"
                },
                {
                    date: "Working on",
                    title: "Albius",
                    description: "We are developing and switching to Albius, a new installer backend for Vanilla OS.",
                    className: "timeline-green"
                },
                {
                    date: "Working on",
                    title: "Ikaros",
                    description: "We are working on a new drivers backend for Vanilla OS",
                    className: "timeline-green"
                },
                {
                    date: "Working on",
                    title: "ABRoot v2",
                    description: "We are working on a new ABRoot version which use OCI images instead of the package manager.",
                    className: "timeline-green"
                },
                {
                    date: "30 April 2023",
                    title: "Prometheus",
                    description: "We are developing a runtime for containers to be used in Vanilla OS projects.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "14 April 2023",
                    title: "Atlas",
                    description: "We are developing a web platform to browse the Vanilla OS Image Registry.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "3 April 2023",
                    title: "Eratosthenes",
                    description: "We are developing a web platform to index and search for packages in the Vanilla OS repositories.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "March 2023",
                    title: "OEM Support",
                    description: "We are working on adding OEM support to Vanilla OS.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "26 February 2023",
                    title: "Setting up testing infrastructure",
                    description: "We are setting up a testing infrastructure to test the new features and bug fixes. The base system is based on Debian sid.",
                    className: "timeline-dimmed-green"
                },
                {
                    date: "25 February 2023",
                    title: "Vanilla OS 2.0 (Orchid) initial work",
                    description: "Initial works on the next major release of Vanilla OS.",
                    className: "timeline-dimmed-green"
                }
            ]
        },
        "#timeline_2"
    );
</script>
