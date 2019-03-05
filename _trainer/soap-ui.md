---
layout: default
name: 'Soap UI'
position: Trainer
company: Accenture
duration: 16 horas
date: 2016-11-07
header:
  teaser: /assets/images/soapui-logo.jpg
sidebar:
  - title: "Role"
    image: /assets/images/soapui-logo.jpg
    text: "Trainer"
  - title: level
    text: level_advance
  - title: go_for
    text: soap_go_for
accordion:
    - item:
        name: soap_concepts
        haschildren: true
        subitems:
            - item:
                name: soap_xml
                haschildren: false
            - item:
                name: soap_web_serv
                haschildren: false
            - item:
                name: soap_desc_lang
                haschildren: false
            - item:
                name: soap_version
                haschildren: false
    - item:
        name: soap_starting
        haschildren: true
        subitems:
            - item:
                name: soap_ide
                haschildren: false
            - item:
                name: soap_create
                haschildren: false
            - item:
                name: soap_wsdl
                haschildren: false
            - item:
                name: soap_apache_cxf
                haschildren: false
            - item:
                name: soap_operations
                haschildren: true
                subitems:
                    - item:
                        name: soap_mock_request
                        haschildren: false
                    - item:
                        name: soap_messages
                        haschildren: true
                        subitems:
                            - item:
                                name: XPath
                                haschildren: false
                            - item:
                                name: XQuery
                                haschildren: false
                    - item:
                        name: soap_scripts
                        haschildren: false
    - item:
        name: soap_test_suites
        haschildren: true
    - item:
        name: soap_test_steps
        haschildren: true
    - item:
        name: soap_test_case_props
        haschildren: true
    - item:
        name: soap_assert_types
        haschildren: true
        subitems:
            - item:
                name: soap_assert_xpath
                haschildren: false
            - item:
                name: soap_assert_xquery
                haschildren: false
            - item:
                name: soap_assert_sla
                haschildren: false
            - item:
                name: soap_assert_xsd
                haschildren: false
            - item:
                name: soap_assert_http_code
                haschildren: false
            - item:
                name: soap_assert_soap
                haschildren: false
            - item:
                name: soap_assert_chain
                haschildren: false
    - item:
        name: soap_exec_test_suites
        haschildren: true
        subitems:
            - item:
                name: soap_exec_simple_exec
                haschildren: false
            - item:
                name: soap_exec_test_case_debug
                haschildren: false
            - item:
                name: soap_modularice
                haschildren: false
            - item:
                name: soap_config_env
                haschildren: false
            - item:
                name: soap_report
                haschildren: false
            - item:
                name: Test on Demand
                haschildren: false
            - item:
                name: soap_log
                haschildren: false
            - item:
                name: Scripting
                haschildren: false
    - item:
        name: soap_config_prefs
        haschildren: true
        subitems:
            - item:
                name: soap_http_proxy
                haschildren: false
            - item:
                name: soap_ssl_prefs
                haschildren: false
            - item:
                name: soap_graphic_interf
                haschildren: false
            - item:
                name: soap_tools_pref
                haschildren: false
            - item:
                name: soap_global_pref
                haschildren: false
    - item:
        name: soap_test_steps
        haschildren: true
        subitems:
            - item:
                name: soap_request_sampling
                haschildren: false
            - item:
                name: soap_trans_properties
                haschildren: false
            - item:
                name: soap_goto
                haschildren: false
            - item:
                name: soap_test_ste_props
                haschildren: false
            - item:
                name: soap_delay_test_steps
                haschildren: false
    - item:
        name: soap_load_test_perform
        haschildren: true
        subitems:
            - item:
                name: soap_load_test_types
                haschildren: true
                subitems:
                    - item:
                        name: soap_load
                        haschildren: false
                    - item:
                        name: soap_stress
                        haschildren: false
                    - item:
                        name: soap_stackoverflow
                        haschildren: false
                    - item:
                        name: soap_scalability
                        haschildren: false
            - item:
                name: soap_load_strategy
                haschildren: false
            - item:
                name: soap_asserts_load
                haschildren: false
            - item:
                name: soap_interpret_results
                haschildren: false
    - item:
        name: soap_security
        haschildren: true
        subitems:
            - item:
                name: soap_sec_sql
                haschildren: false
            - item:
                name: soap_sec_xpath
                haschildren: false
            - item:
                name: soap_sec_script
                haschildren: false
            - item:
                name: soap_sec_fuzz
                haschildren: false
            - item:
                name: soap_sec_xml_malformed
                haschildren: false
    - item:
        name: soap_test_automatic
        haschildren: true
        subitems:
            - item:
                name: soap_int_test_case_ju
                haschildren: false
            - item:
                name: soap_int_test_case_mvn
                haschildren: false
            - item:
                name: soap_int_test_case_other
                haschildren: false
    - item:
        name: soap_ddd
        haschildren: true
        subitems:
            - item:
                name: JDBC
                haschildren: false
            - item:
                name: soap_ddd_files
                haschildren: false
    - item:
        name: soap_test_case_odd
        haschildren: true
        subitems:
            - item:
                name: soap_odd_wsdl
                haschildren: false
            - item:
                name: soap_odd_sql
                haschildren: false
            - item:
                name: soap_odd_xpath
                haschildren: false
            - item:
                name: soap_odd_ddd
                haschildren: false
            - item:
                name: soap_odd_http
                haschildren: false
            - item:
                name: soap_http_form
                haschildren: false
            - item:
                name: soap_oauth_two
                haschildren: false
            - item:
                name: soap_session
                haschildren: false
---

<div id="main" role="main">
    {% include sidebar.html %}
    <article class="page" itemscope itemtype="https://schema.org/CreativeWork">
      <meta itemprop="headline" content="{{ page.name }}"/>
      <meta itemprop="description" content="{{ page.header.description }}"/>
      <div class="page__inner-wrap">
        <header>
          <h1 id="page-title" class="page__title" itemprop="headline">{{ page.name }}</h1>
        </header>
        <section class="page__content" itemprop="text">
            <p>SoapUI is a tool for testing Web Services; these can be the SOAP Web Services as well RESTful Web Services or HTTP based services. SoapUI is an Open Source and completely free tool with a commercial companion -SoapUI Pro- that has extra functionality for companies with mission critical Web Services.</p>
            <p>SoapUI has been downloaded more than 3 million times and is seen as the de facto standard for API Service Testing. </p>

          <h3 id="page-title" class="page__title" itemprop="headline" style="margin-bottom: 0.7em;">Temario</h3>     
          {% include accordion include_scripts=true %}
        </section>
      </div>
    </article>
</div>