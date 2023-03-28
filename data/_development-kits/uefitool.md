---
layout: post
title: "Download UEFITool"
description: UEFITool is a cross-platform application that allows you to view, tweak, and manipulate UEFI firmware images. Learn more about this powerful firmware analysis tool in this article.
date: 2023-03-26 06:30:38 +0300
last_modified_at: 2023-03-26 19:00:25 +0300
slug: uefitool
cat: development-kits
name: "UEFITool"
dev: ""
link: ""
article: "RnJlZSBVRUZJIGltYWdlIGVkaXRvclVFRklUb29sLCBsaWtlIFZlbnRveSBhbmQgQm9vdC1SZXBhaXItRGlzaywgaXMgYSBmcmVlIFVFRkkgbW9kaWZpY2F0aW9uIHRoYXQgZ2l2ZXMgeW91IGFjY2VzcyB0byBVRUZJLWNvbXBhdGlibGUgdXRpbGl0aWVzLiBPbiBXaW5kb3dzLCBpdCBmZWF0dXJlcyBhIHNpbXBsZSBpbnRlcmZhY2UgdGhhdCBhbGxvd3MgeW91IHRvIGFuYWx5emUsIGVkaXQsIGFuZCB2aWV3IEJJT1MgaW1hZ2VzIGFuZCBVRUZJIGZpcm13YXJlIHNldHRpbmdzLiBUaGUga2V5IGlzIHRvIGltcG9ydCB0aGUgZGF0YSBpbnRvIHBpY3R1cmUgZmlsZXMsIHdoaWNoIGNhbiB0aGVuIHNlcnZlIGFzIHRoZSBmb3VuZGF0aW9uIGZvciBjdXN0b21pemluZyB0aGVtLsKgUHJvZmVzc2lvbmFscyBnZW5lcmFsbHkgY2hhbmdlIFVFRkkgZmlybXdhcmUsIGhvd2V2ZXIsIFVFRklUb29sIG1ha2VzIGl0IHNpbXBsZSBmb3IgYmVnaW5uZXJzIHRvIHVuZGVyc3RhbmQgaG93IGl0IHdvcmtzLiBJdCdzIGFsc28gY29tcGF0aWJsZSB3aXRoIGEgdmFyaWV0eSBvZiBCSU9TIHR5cGVzIGFuZCBvZmZlcnMgcGxlbnR5IG9mIG90aGVyIGZlYXR1cmVzLiBZb3UgaGF2ZSB0aGUgb3B0aW9uIG9mIHVzaW5nIHRoZSByZWd1bGFyIG9yIGFkdmFuY2VkIHNldHRpbmdzLnNhbS5jbWQucHVzaChmdW5jdGlvbigpIHsgc2FtLmRpc3BsYXkoJ3Jldmlldy1hcHAtcGFnZS1kZXNrdG9wJyk7IH0pO0hvdyBkbyBJIGVkaXQgVUVGST9Xb3JraW5nIHdpdGggQklPUyBzZXR0aW5ncyBtYXkgYmUgY2hhbGxlbmdpbmcsIGVzcGVjaWFsbHkgaWYgeW91J3JlIG5vdCBmYW1pbGlhciB3aXRoIHRoZSBwcm9jZWR1cmUuIFRoZSBnb2FsIG9mIFVFRklUb29sIGlzIHRvIG1ha2UgdGhlIHByb2Nlc3MgZWFzaWVyIGJ5IHByb3ZpZGluZyB0aGUgYmVzdCB0ZWNobmlxdWVzIGZvciBpbnRlcnByZXRpbmcgYW5kIGNoYW5naW5nIHNldHRpbmdzIHdpdGhvdXQgY2F1c2luZyBhbnkgaGFybS4gWW91J2xsIGp1c3QgaW1wb3J0IGZpbGVzIGFzIGltYWdlcyBhbmQgbWFrZSBjaGFuZ2VzIGJlZm9yZSBleHBvcnRpbmcgdGhlbSBhZ2Fpbi4gVGhlIHVzZXItZnJpZW5kbHkgVUVGSVRvb2wgaW50ZXJmYWNlIGlzIHRoZSBmaXJzdCBjb21wb25lbnQgdGhhdCBtYWtlcyBVRUZJLWNoYW5naW5nIHNpbXBsZSBmb3IgeW91LsKgRXZlcnl0aGluZyBpcyB3ZWxsIGxhaWQgb3V0IGluIHdpbmRvd3Mgd2hlcmUgeW91IGNhbiBnZXQgYWxsIG9mIHRoZSBpbmZvcm1hdGlvbiB5b3UgbmVlZCB0byBnZXQgeW91IHN0YXJ0ZWQuIE9mIGNvdXJzZSwgYmVmb3JlIHlvdSBjYW4gbWFrZSBhbnkgY2hhbmdlcywgeW91J2xsIG5lZWQgdG8gY29tcHJlaGVuZCB3aGF0IHlvdSdyZSBsb29raW5nIGF0LiBVRUZJVG9vbCBkaXNwbGF5cyB0aGUgZGF0YSBpbiBhbiBlYXN5LXRvLXJlYWQgbWFubmVyLiBJbWFnZXMsIHN1Y2ggYXMgQklOLCBCSU8sIFJPTSwgQ0FQLCBXUEgsIEZELCBhbmQgRUZJIGFyZSBzb21lIG9mIHRoZSBpbWFnZSB0eXBlcyB5b3UgY2FuIGV4cGVyaW1lbnQgd2l0aCB1c2luZyB0aGlzIHRvb2wuQXMgbG9uZyBhcyB5b3Uga25vdyB3aGF0IHlvdSdyZSBkb2luZywgeW91IGNhbiBhZGQgYW5kIGRlbGV0ZSBjb21wb25lbnRzIGFzIHlvdSBzZWUgYXBwcm9wcmlhdGUuIEFmdGVyIHlvdSBoYXZlIHRoZSBuZWNlc3NhcnkgY2hhbmdlcywgeW91IGhhdmUgdGhlIG9wdGlvbiB0byBlaXRoZXIgc2F2ZSB5b3VyIEJJT1MgaW1hZ2VzIGFuZCBVRUZJIGZpcm13YXJlIHNldHRpbmdzIHRvIHlvdXIgV2luZG93cyBkZXZpY2Ugb3IgYW4gZXh0ZXJuYWwgVVNCIGRyaXZlIGFzIHRoZSBsYXN0IHN0ZXAuIElmIHlvdSB3aXNoIHRvIHNlZWsgb3RoZXIgZGV2ZWxvcGVycycgZmVlZGJhY2sgb24gdGhlIGNoYW5nZXMsIHlvdSBtYXkgYWxzbyBzaGFyZSBpdCBwdWJsaWNseS5FYXNpbHkgY2hhbmdlIHlvdXIgVUVGSSBmaXJtd2FyZcKgRm9yIHRob3NlIHdobyBmaW5kIG1ha2luZyBVRUZJIGNoYW5nZXMgdGlyZXNvbWUgYW5kIHNvbWV3aGF0IGNvbXBsaWNhdGVkLCBVRUZJVG9vbCB3aWxsIHNlcnZlIGFzIGFuIGV4Y2VsbGVudCBzb2x1dGlvbiBmb3IgeW91LiBZb3UnbGwgaGF2ZSBhIGJhc2ljIHVzZXIgaW50ZXJmYWNlIHRoYXQgZWFzeSB0byB1bmRlcnN0YW5kIGFuZCBuYXZpZ2F0ZSwgbWFraW5nIHlvdXIgam9iIGEgbG90IGVhc2llci4gV2hhdCdzIG1vcmUsIHlvdSdsbCBiZSBhYmxlIHRvIGV4cG9ydCBhbnkgb2YgeW91ciB3b3JrIHF1aWNrbHkgYWZ0ZXIgeW91J3JlIGZpbmlzaGVkLiBJdCdzIGFsc28gYmVuZWZpY2lhbCB0byB0aG9zZSB3aG8gd2lzaCB0byBsZWFybiBhbmQgcHJhY3RpY2UgaGFuZGxpbmcgdGhpcyB0eXBlIG9mIHRvb2wu"
img: "https://images.sftcdn.net/images/t_app-cover-l,f_auto/p/beca6d85-2d0b-44f1-974b-3725577f8a80/3449803432/uefitool-screenshot.jpg"
use_article: no
published: true
---
## Introduction

UEFITool is a cross-platform application that allows you to view, tweak, and manipulate UEFI firmware images. With UEFITool, you can easily explore the contents of firmware images, extract files, and even patch firmware to enable new functionality or fix issues. In this article, we'll take a closer look at UEFITool and how it can be used in firmware analysis.

## The Features of UEFITool

UEFITool provides a variety of features for working with UEFI firmware images. Some of the most notable features include:

- **Full UEFI firmware support:** UEFITool supports all types of UEFI firmware, including AMI Aptio, Insyde H2O, Phoenix SecureCore, and more.
- **Easy file extraction:** With UEFITool, you can easily extract individual files from firmware images by simply drag-and-dropping them to a folder on your computer.
- **Powerful firmware analysis:** UEFITool provides a powerful Hex Editor that enables you to view and edit the contents of firmware images in detail.
- **UEFI firmware patching:** UEFITool allows you to patch UEFI firmware images to enable new functionality or fix issues. This can include modifying the contents of various firmware modules or even adding new modules to the firmware image.
- **Cross-platform compatibility:** UEFITool is available for Windows, Linux, and macOS, ensuring that it can be used on a wide range of systems.

## How to Use UEFITool

Using UEFITool is straightforward. To get started, simply download the appropriate version of the application for your platform, then launch it. From there, you can open a firmware image file by selecting File -> Open from the menu.

Once you have opened a firmware image file, you can begin exploring its contents. This can be done by simply expanding the folders within the firmware image using the Tree view. You can also use the Hex Editor to view and edit the contents of individual firmware modules.

If you want to extract a file or module from the firmware image, simply drag-and-drop it to a folder on your computer. If you want to patch the firmware image, you can use the Hex Editor or other UEFITool features to make changes, then save the modified firmware image file.

## Conclusion

UEFITool is a powerful firmware analysis tool that provides a wide range of features for exploring, extracting, and patching UEFI firmware images. With its cross-platform compatibility and easy-to-use interface, UEFITool is an excellent choice for anyone working with UEFI firmware. Whether you're a firmware developer, an IT professional, or simply interested in learning more about UEFI firmware, UEFITool is a valuable tool to have in your arsenal.