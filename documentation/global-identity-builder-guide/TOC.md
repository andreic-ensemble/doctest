---
title: Global Identity Builder Guide TOC
description: Global Identity Builder Guide TOC Description
---

[Chapter 1: Introduction [3](#chapter-1-introduction)](/global-identity-builder-guide/chapter-1-introduction)

[Accessing the Global Identity Builder Tool [5](#accessing-the-global-identity-builder-tool)](/global-identity-builder-guide/accessing-the-global-identity-builder-tool)

[Chapter 2: Concepts [6](#chapter-2-concepts)](/global-identity-builder-guide/chapter-2-concepts)

[Project [6](#project)](/global-identity-builder-guide/project)

[Identity Correlation [6](#identity-correlation)](/global-identity-builder-guide/identity-correlation)

[Identity Source [6](#identity-source)](#identity-source)

[Identity Source Browser [6](#identity-source-browser)](#identity-source-browser)

[Global Profile [7](#global-profile)](#global-profile)

[Global Profile Browser [7](#global-profile-browser)](#global-profile-browser)

[Unresolved Identity [8](#unresolved-identity)](#unresolved-identity)

[Persistent Cache [8](#persistent-cache)](#persistent-cache)

[Correlation Rule [8](#correlation-rule)](#correlation-rule)

[Attribute Mapping [8](#attribute-mapping)](#attribute-mapping)

[Bind Order [9](#bind-order)](#bind-order)

[Attribute Priority [9](#_Toc97028583)](#_Toc97028583)

[VUID [10](#vuid)](#vuid)

[Global Identity Viewer [11](#global-identity-viewer)](#global-identity-viewer)

[Chapter 3: Creating Projects [13](#chapter-3-creating-projects)](#chapter-3-creating-projects)

[Project Properties [13](#project-properties)](#project-properties)

[Project Name [14](#project-name)](#project-name)

[Naming Context [14](#naming-context)](#naming-context)

[Global Profile Object Class [14](#global-profile-object-class)](#global-profile-object-class)

[Additional Object Classes [14](#additional-object-classes)](#additional-object-classes)

[Login Attributes [15](#login-attributes)](#login-attributes)

[Display/Search Attribute [15](#displaysearch-attribute)](#displaysearch-attribute)

[Custom Attributes [15](#custom-attributes)](#custom-attributes)

[Runtime Optimizations [16](#runtime-optimizations)](#runtime-optimizations)

[Identity Sources [16](#identity-sources)](#identity-sources)

[Attribute Mappings [18](#attribute-mappings)](#attribute-mappings)

[Correlation Rules [21](#_Toc97028598)](#_Toc97028598)

[Define Attribute Priority [25](#define-attribute-priority)](#define-attribute-priority)

[Upload [26](#upload)](#upload)

[Bulk Upload [28](#bulk-upload)](#bulk-upload)

[Single Uploads [29](#single-uploads)](#single-uploads)

[Upload Behavior [29](#upload-behavior)](#upload-behavior)

[Upload Logs [31](#upload-logs)](#upload-logs)

[Define Bind Order [31](#define-bind-order)](#define-bind-order)

[Test Authentication [32](#test-authentication)](#test-authentication)

[Chapter 4: Manual Identity Administration [33](#chapter-4-manual-identity-administration)](#chapter-4-manual-identity-administration)

[Removing Identities from the Global Profile [33](#removing-identities-from-the-global-profile)](#removing-identities-from-the-global-profile)

[Identity Unlinking [33](#identity-unlinking)](#identity-unlinking)

[Viewing Unresolved Identities [34](#viewing-unresolved-identities)](#viewing-unresolved-identities)

[Adding Unresolved Identities into the Global Profile [35](#adding-unresolved-identities-into-the-global-profile)](#adding-unresolved-identities-into-the-global-profile)

[Login Conflict Analysis [36](#login-conflict-analysis)](#login-conflict-analysis)

[Launch Login Analysis [38](#launch-login-analysis)](#launch-login-analysis)

[Chapter 5: Persistent Cache with Real-Time Refresh [39](#chapter-5-persistent-cache-with-real-time-refresh)](#chapter-5-persistent-cache-with-real-time-refresh)

[Configuring Real-time Persistent Cache Refresh [39](#configuring-real-time-persistent-cache-refresh)](#configuring-real-time-persistent-cache-refresh)

[Re-configuring Project Properties [40](#re-configuring-project-properties)](#re-configuring-project-properties)

[Real-time Persistent Cache Refresh Impact on Global Profile Identities [40](#real-time-persistent-cache-refresh-impact-on-global-profile-identities)](#real-time-persistent-cache-refresh-impact-on-global-profile-identities)

[Identity Source Logs [42](#identity-source-logs)](#identity-source-logs)

[Chapter 6: Linking Existing Groups to Global Profile Identities [43](#chapter-6-linking-existing-groups-to-global-profile-identities)](#chapter-6-linking-existing-groups-to-global-profile-identities)

[Creating a Root Naming Context for Global Profile Identities and Groups [44](#creating-a-root-naming-context-for-global-profile-identities-and-groups)](#creating-a-root-naming-context-for-global-profile-identities-and-groups)

[Defining Computed Group Membership [49](#defining-computed-group-membership)](#defining-computed-group-membership)

[Testing the Result [51](#testing-the-result)](#testing-the-result)

[Appendix A: Integrating a Custom Data Source [53](#appendix-a-integrating-a-custom-data-source)](#appendix-a-integrating-a-custom-data-source)

[Overview [53](#overview)](#overview)

[Configuration [53](#configuration)](#configuration)

[Custom Data Source [53](#custom-data-source)](#custom-data-source)

[Create Virtual View [54](#create-virtual-view)](#create-virtual-view)

[Configure Persistent Cache [58](#configure-persistent-cache)](#configure-persistent-cache)

[Add RadiantOne Cache as an Identity Source in the Project [58](#add-radiantone-cache-as-an-identity-source-in-the-project)](#add-radiantone-cache-as-an-identity-source-in-the-project)

[Appendix B: Addressing Group Membership Challenges [60](#appendix-b-addressing-group-membership-challenges)](#appendix-b-addressing-group-membership-challenges)

[LDAP Dynamic Groups [60](#ldap-dynamic-groups)](#ldap-dynamic-groups)

[Nested Groups [63](#nested-groups)](#nested-groups)

[Users and Groups Distributed in Multiple Containers [69](#users-and-groups-distributed-in-multiple-containers)](#users-and-groups-distributed-in-multiple-containers)

[Appendix C: Extending the Global Profile View [72](#appendix-c-extending-the-global-profile-view)](#appendix-c-extending-the-global-profile-view)
