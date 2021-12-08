# PeopleSoft Project Object Listing Utility
An Application Engine process to write a list of objects contained within a project. This includes the object type, object name, type, description (if applicable), and action.

Files contained in this git:
<ul>
<li>.zip file is the complete PeopleSoft project including the application engine, run control page, etc, ready to be imported. This has been exported with PeopleTools 8.56. 
<li>.txt file is the PeopleCode listing alone.</li>
<li>.xls file is a sample of the output from the process</li>
</ul>

And here is the object type mapping I've been able to pull together, so far:
    
<table>
    <thead>
        <tr>
            <th>Object Type</th>
            <th>Object Description</th>
            <th>Source Table</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>0</td>
            <td>Record</td>
            <td>PSRECDEFN</td>
        </tr>
        <tr>
            <td>1</td>
            <td>Index</td>
            <td>PSINDEXDEFN</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Field</td>
            <td>PSDBFIELD</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Field Format</td>
            <td>PSFMTDEFN</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Translate Value</td>
            <td>PSXLATITEM</td>
        </tr>
        <tr>
            <td>5</td>
            <td>Page</td>
            <td>PSPNLDEFN</td>
        </tr>
        <tr>
            <td>6</td>
            <td>Menu</td>
            <td>PSMENUDEFN</td>
        </tr>
        <tr>
            <td>7</td>
            <td>Component</td>
            <td>PSPNLGRPDEFN</td>
        </tr>
        <tr>
            <td>8</td>
            <td>Record PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>9</td>
            <td>Menu PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>10</td>
            <td>Query</td>
            <td>PSQRYDEFN</td>
        </tr>
        <tr>
            <td>11</td>
            <td>Tree Structure</td>
            <td>PSTREESTRCT</td>
        </tr>
        <tr>
            <td>12</td>
            <td>Tree</td>
            <td>PSTREEDEFN</td>
        </tr>
        <tr>
            <td>13</td>
            <td>Access Group</td>
            <td>PS_ACCESS_GRP_TBL</td>
        </tr>
        <tr>
            <td>14</td>
            <td>Color</td>
            <td>PSCOLORDEFN</td>
        </tr>
        <tr>
            <td>15</td>
            <td>Style</td>
            <td>PSSTYLEDEFN</td>
        </tr>
        <tr>
            <td>16</td>
            <td>Not Used</td>
            <td>-</td>
        </tr>
        <tr>
            <td>17</td>
            <td>Business Process</td>
            <td>PSBUSPROCDEFN</td>
        </tr>
        <tr>
            <td>18</td>
            <td>Activity</td>
            <td>PSACTIVITYDEFN</td>
        </tr>
        <tr>
            <td>19</td>
            <td>Roles</td>
            <td>PSROLEDEFN</td>
        </tr>
        <tr>
            <td>20</td>
            <td>Process Definitions</td>
            <td>PS_PRCSDEFN</td>
        </tr>
        <tr>
            <td>21</td>
            <td>Servers</td>
            <td>PS_SERVERDEFN</td>
        </tr>
        <tr>
            <td>22</td>
            <td>Process Types</td>
            <td>PS_PRCSTYPEDEFN</td>
        </tr>
        <tr>
            <td>23</td>
            <td>Job Definitions</td>
            <td>PS_PRCSJOBDEFN</td>
        </tr>
        <tr>
            <td>24</td>
            <td>Recurrences</td>
            <td>PS_PRCSRECUR</td>
        </tr>
        <tr>
            <td>25</td>
            <td>Message Catalog</td>
            <td>PSMSGCATDEFN</td>
        </tr>
        <tr>
            <td>26</td>
            <td>Dimension</td>
            <td>PS_DIMENSION</td>
        </tr>
        <tr>
            <td>27</td>
            <td>Cube Definition</td>
            <td>PSACECUBE</td>
        </tr>
        <tr>
            <td>28</td>
            <td>Cube Instance</td>
            <td>PS_ANALYSIS_DB</td>
        </tr>
        <tr>
            <td>29</td>
            <td>Business Interlink</td>
            <td>PSIODEFN</td>
        </tr>
        <tr>
            <td>30</td>
            <td>SQL</td>
            <td>PSSQLDEFN</td>
        </tr>
        <tr>
            <td>31</td>
            <td>File Layout</td>
            <td>PSFLDDEFN</td>
        </tr>
        <tr>
            <td>32</td>
            <td>Component Interface</td>
            <td>PSBCDEFN</td>
        </tr>
        <tr>
            <td>33</td>
            <td>Application Engine Program</td>
            <td>PSAEAPPLDEFN</td>
        </tr>
        <tr>
            <td>34</td>
            <td>Application Engine Section</td>
            <td>PSAESECTDEFN</td>
        </tr>
        <tr>
            <td>35</td>
            <td>Message Node</td>
            <td>PSMSGNODEDEFN</td>
        </tr>
        <tr>
            <td>36</td>
            <td>Message Channel</td>
            <td>PSMSGDEFN</td>
        </tr>
        <tr>
            <td>37</td>
            <td>Message</td>
            <td>PSMSGDEFN</td>
        </tr>
        <tr>
            <td>38</td>
            <td>Approval Rule Set</td>
            <td>PS_APPR_RULE_HDR</td>
        </tr>
        <tr>
            <td>39</td>
            <td>Message PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>40</td>
            <td>Subscription PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>41</td>
            <td>Not Used</td>
            <td>-</td>
        </tr>
        <tr>
            <td>42</td>
            <td>Component Interface PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>43</td>
            <td>Application Engine PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>44</td>
            <td>Page PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>45</td>
            <td>Page Field PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>46</td>
            <td>Component PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>47</td>
            <td>Component Record PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>48</td>
            <td>Component Rec Field PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>49</td>
            <td>Image</td>
            <td>PSCONTDEFN</td>
        </tr>
        <tr>
            <td>50</td>
            <td>Style Sheet</td>
            <td>STYLESHEETTYPE</td>
        </tr>
        <tr>
            <td>51</td>
            <td>HTML</td>
            <td>PSCONTDEFN</td>
        </tr>
        <tr>
            <td>52</td>
            <td>Not Used</td>
            <td>-</td>
        </tr>
        <tr>
            <td>53</td>
            <td>Permission List</td>
            <td>PSCLASSDEFN</td>
        </tr>
        <tr>
            <td>54</td>
            <td>Portal Registry Definition</td>
            <td>PSPRDMDEFN</td>
        </tr>
        <tr>
            <td>55</td>
            <td>Portal Registry Structure</td>
            <td>PSPRSMDEFN</td>
        </tr>
        <tr>
            <td>56</td>
            <td>URL Definition</td>
            <td>PSURLDEFN</td>
        </tr>
        <tr>
            <td>57</td>
            <td>Application Package</td>
            <td>PSPACKAGEDEFN</td>
        </tr>
        <tr>
            <td>58</td>
            <td>Application Package PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>59</td>
            <td>Portal Registry User Homepage</td>
            <td>PSPRUHDEFN</td>
        </tr>
        <tr>
            <td>60</td>
            <td>Analytic Type</td>
            <td>PSOPTPRBTYPE</td>
        </tr>
        <tr>
            <td>61</td>
            <td>Archive Template</td>
            <td>PS_ARCH_PROJ</td>
        </tr>
        <tr>
            <td>62</td>
            <td>XSLT</td>
            <td>PSSQLDEFN</td>
        </tr>
        <tr>
            <td>63</td>
            <td>Portal Registry User Favorite</td>
            <td>PSPRUFDEFN</td>
        </tr>
        <tr>
            <td>64</td>
            <td>Mobile Page</td>
            <td>PSMPDEFN</td>
        </tr>
        <tr>
            <td>65</td>
            <td>Relationships</td>
            <td>PSRELATIONSHIP</td>
        </tr>
        <tr>
            <td>66</td>
            <td>Component Interface Property PeopleCode</td>
            <td>PSPCMPROG</td>
        </tr>
        <tr>
            <td>67</td>
            <td>Optimization Model</td>
            <td>PSOPTMODEL</td>
        </tr>
        <tr>
            <td>68</td>
            <td>File References</td>
            <td>PSFILEREDEFN</td>
        </tr>
        <tr>
            <td>69</td>
            <td>File Type Codes</td>
            <td>PSTYPECODEDEFN</td>
        </tr>
        <tr>
            <td>70</td>
            <td>Archive Object</td>
            <td>PSARCHOBJDEFN</td>
        </tr>
        <tr>
            <td>71</td>
            <td>Archive Templates (Type 2)</td>
            <td>PSARCHTEMPLATE</td>
        </tr>
        <tr>
            <td>72</td>
            <td>Diagnostic Plug-ins</td>
            <td>PSDIAGREG</td>
        </tr>
        <tr>
            <td>73</td>
            <td>Analytic Model</td>
            <td>PSACEMDLDEFN</td>
        </tr>
        <tr>
            <td>74</td>
            <td>Not Used</td>
            <td>-</td>
        </tr>
        <tr>
            <td>75</td>
            <td>Java Portlet User Preferences</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>76</td>
            <td>WSRP Remote Producers</td>
            <td>PSWSRPPRDDEFN</td>
        </tr>
        <tr>
            <td>77</td>
            <td>WSRP Remote Portlets</td>
            <td>PSWSRPPLTDEFN</td>
        </tr>
        <tr>
            <td>78</td>
            <td>WSRP Cloned Portlet Handles</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>79</td>
            <td>Service</td>
            <td>PSSERVICE</td>
        </tr>
        <tr>
            <td>80</td>
            <td>Service Operation</td>
            <td>PSOPERATION</td>
        </tr>
        <tr>
            <td>81</td>
            <td>Service Operation Handler</td>
            <td>PSOPRHDLR</td>
        </tr>
        <tr>
            <td>82</td>
            <td>Service Operation Version</td>
            <td>PSOPRVERDFN</td>
        </tr>
        <tr>
            <td>83</td>
            <td>Service Operation Routing</td>
            <td>PSIBRTNGDEFN</td>
        </tr>
        <tr>
            <td>84</td>
            <td>IB Queues</td>
            <td>PSQUEUEDEFN</td>
        </tr>
        <tr>
            <td>85</td>
            <td>BIP Template Definition</td>
            <td>PSXPTMPLDEFN</td>
        </tr>
        <tr>
            <td>86</td>
            <td>BIP Report Definition</td>
            <td>PSXPRPTDEFN</td>
        </tr>
        <tr>
            <td>87</td>
            <td>BIP File Definition</td>
            <td>PSFILEDEFN</td>
        </tr>
        <tr>
            <td>88</td>
            <td>BIP Data Source Definitions</td>
            <td>PSXPDATASRC</td>
        </tr>
        <tr>
            <td>89</td>
            <td>WSDL</td>
            <td>PSIBWSDLDFN</td>
        </tr>
        <tr>
            <td>90</td>
            <td>Message Schema</td>
            <td>PSIBSCMADFN</td>
        </tr>
        <tr>
            <td>91</td>
            <td>Connected Query</td>
            <td>PSCONQRSDEFN</td>
        </tr>
        <tr>
            <td>92</td>
            <td>Logical Schema</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>93</td>
            <td>XML Schema</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>94</td>
            <td>Relational Schema</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>95</td>
            <td>Dependency Document</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>96</td>
            <td>Document Schema</td>
            <td>PSLSDEFN</td>
        </tr>
        <tr>
            <td>97</td>
            <td>Essbase Cube Dimension</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>98</td>
            <td>Essbase Cube Outline</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>99</td>
            <td>Essbase Cube Connection</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>100</td>
            <td>Essbase Cube Template</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>101</td>
            <td>Delimited Schema</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>102</td>
            <td>Positional Schema</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>103</td>
            <td>Data Set Definition</td>
            <td>PSADSDEFN</td>
        </tr>
        <tr>
            <td>104</td>
            <td>Test</td>
            <td>PSPTTSTDEFN</td>
        </tr>
        <tr>
            <td>105</td>
            <td>Test Case</td>
            <td>PSPTTSTCASE</td>
        </tr>
        <tr>
            <td>106</td>
            <td>Application Data Set Binding</td>
            <td>PSPROJBINDITEM</td>
        </tr>
        <tr>
            <td>107</td>
            <td>Feed Definition</td>
            <td>PSFP_FEED</td>
        </tr>
        <tr>
            <td>108</td>
            <td>Feed Category</td>
            <td>PSFP_CATEGORY</td>
        </tr>
        <tr>
            <td>109</td>
            <td>Feed Data Type</td>
            <td>PSFP_DATATYPE</td>
        </tr>
        <tr>
            <td>110</td>
            <td>JSON Document</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>111</td>
            <td>Related Content Definition</td>
            <td>PSPTCSSRVDEFN</td>
        </tr>
        <tr>
            <td>112</td>
            <td>Related Content Services</td>
            <td>PSPTCS_SRVCFG</td>
        </tr>
        <tr>
            <td>113</td>
            <td>Related Content Configuration</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>114</td>
            <td>Related Content Layout</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>115</td>
            <td>Search Attribute</td>
            <td>PSPTSF_ATTRS</td>
        </tr>
        <tr>
            <td>116</td>
            <td>Search Definition</td>
            <td>PSPTSF_SD</td>
        </tr>
        <tr>
            <td>117</td>
            <td>Search Category</td>
            <td>PSPTSF_SRCCAT</td>
        </tr>
        <tr>
            <td>118</td>
            <td>Search Context</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>119</td>
            <td>Integration Group</td>
            <td>PSIBGROUPDEFN</td>
        </tr>
        <tr>
            <td>120</td>
            <td>XML Documents</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>121</td>
            <td>MAP Layouts</td>
            <td>PSDOCLODEFN</td>
        </tr>
        <tr>
            <td>122</td>
            <td>MAP Template</td>
            <td>TBD</td>
        </tr>
        <tr>
            <td>123</td>
            <td>Composite Query</td>
            <td>PSCPQDEFN</td>
        </tr>
        <tr>
            <td>125</td>
            <td>MAP Admin</td>
            <td>PSMAPMDEFN</td>
        </tr>
        <tr>
            <td>126</td>
            <td>MAP Store</td>
            <td>PSMAPSDEFN</td>
        </tr>
    </tbody>
</table>
